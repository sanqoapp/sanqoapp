<p align="center">
  <a href="https://sanqo.app"><img src="https://sanqo.app/brand/sanqo-logo.webp" alt="SANQO" width="260"></a>
</p>

<h1 align="center">SANQO</h1>

<p align="center">
  <strong>The intelligent clinical workspace for modern clinics and general practitioners.</strong><br>
  Less paperwork. More consultations. One continuous record per patient.
</p>

<p align="center">
  <a href="https://sanqo.app"><img alt="Website" src="https://img.shields.io/badge/website-sanqo.app-177e70"></a>
  <a href="https://sanqo.app/join-pilot"><img alt="Pilot" src="https://img.shields.io/badge/free%20clinic%20pilot-applications%20open-0b7285"></a>
  <a href="https://sanqo.app/demo"><img alt="Demo" src="https://img.shields.io/badge/try%20the%20workflow-synthetic%20demo-5f6c7b"></a>
  <img alt="Region" src="https://img.shields.io/badge/pilot-Malaysia%20%C2%B7%20Jan–Jun%202027-5f6c7b">
</p>

---

## What SANQO is

**SANQO** — *Smart AI Navigator for Quantifiable Outcomes* — is an AI-assisted clinical workspace for clinics and general practitioners in Southeast Asia.

Most clinic software stores visits. It rarely connects them. Intake sits in one place, the consultation note in another, the prescription in a third, and whether the treatment actually worked is usually never recorded at all. The patient returns and the clinician starts from a blank page.

SANQO closes that gap. It connects **intake → consultation → prescription → follow-up → recorded outcome** into one continuous care journey, so every visit begins with the documented history of the last one.

- **Website:** <https://sanqo.app>
- **Apply for the free clinic pilot:** <https://sanqo.app/join-pilot>
- **Try a workflow (synthetic data):** <https://sanqo.app/demo>
- **Documentation:** <https://sanqo.app/docs>
- **Health guides, resources and blog:** <https://www.eazycare.ai>

> **Status: pre-launch.** The Malaysia pilot runs **January–June 2027**, with partnership onboarding from **December 2026**. Clinical workspace access opens with participating pilot clinics; registering interest does not activate a clinical account.

---

## The connected clinical loop

| Stage | What happens |
|---|---|
| **Before the visit** | Structured intake brings the patient's concerns and history into the consultation, so the clinician is briefed before the patient sits down. |
| **During care** | Review the record, document findings and build a treatment plan — with clinician oversight at every step. |
| **After treatment** | Prescriptions and planned follow-ups stay connected to the encounter that produced them. |
| **Closing the loop** | Record adherence, clinical response and side effects, giving the next visit a better starting point. |

Everything connects to the next step. That continuity is the product.

---

## Features

### For clinics and GPs

- **Today's queue** — live clinic dashboard built from recorded activity: who has arrived, who has completed intake, who is in consultation, and how long each patient has been waiting.
- **QR check-in** — each clinic gets a signed, branded check-in poster. Patients scan, complete intake on their own phone, and arrive in the queue with their reason for visiting already captured.
- **Consultation workspace** — review context, document findings, record a coded diagnosis with explicit certainty, and prescribe with dose, frequency and duration attached to that diagnosis.
- **Follow-ups that close** — recording a treatment course schedules its own follow-up automatically, due after the course ends, so nothing depends on someone remembering.
- **Patient records and verification** — clinic owners verify patient, parent, guardian or caregiver authority before any dependent record is released. Delegated permissions expire after 90 days. No automatic age-based access grants.
- **Insights** — loop-closure rate, follow-ups due and missed, median door-to-doctor time, and encounter volume.
- **Data import and export** — review demographic CSV or pasted-spreadsheet imports, and request structured exports of your own clinic's data. Original-file and full clinical-history migration are assisted workflows.
- **Support with escalation** — in-product case capture, a named onboarding contact, and a defined escalation path for critical incidents.

### For patients and families

- **One continuous health record** — visit records, completed encounter notes, medicines, follow-ups and sharing permissions in a single patient-owned account.
- **Reusable patient profiles** — create your own profile once and reuse it at every participating clinic, with dependent profiles kept separate from your own.
- **Deliberate, category-level sharing** — sharing is recipient-specific, category-specific and explicitly consented, with a chosen expiry of 7, 30 or 90 days. Revocation retires existing shares; the clinic's own retention obligations are unaffected.
- **Follow-up requests** — request an in-person or video follow-up after a completed visit. The clinic assigns a verified clinician and confirms the time; a request is not a guaranteed appointment.
- **Works on the device you already have** — SANQO runs in the browser on phones, tablets and computers, and installs to the home screen as a PWA.

### AI assistance, with the clinician in charge

AI assists the workflow: structuring intake, surfacing relevant history, and reducing documentation load. **It does not make clinical decisions.** Diagnosis, prescribing and every clinical judgement remain the responsibility of the treating clinician, and the interface is built so that approving a plan is always an explicit human action.

The interactive demo at [sanqo.app/demo](https://sanqo.app/demo) uses entirely fictional patients and placeholder medicines. It illustrates record layout and workflow only — it does not generate a diagnosis, simulate a successful allergy or interaction check, or produce a usable prescription.

---

## Privacy and access model

Patient data ownership and clinic tenancy are structural, not configurable:

- **Patients own their record.** Clinic access to a patient-owned profile is granted through signed, scoped visit consent — never through automatic person-matching or cross-clinic record merging.
- **Verified authority for dependents.** A clinic must verify a guardian or caregiver's authority before releasing dependent clinical records.
- **Tamper-evident consent history.** Access and consent events are protected at the database level against ordinary update and deletion.
- **Authenticated sessions, closed by default.** One-time codes are HMAC-protected with bounded attempts and atomic consumption; sessions are server-recorded and revocable. Missing or weak production signing secrets fail closed.
- **Nothing private is cached.** Private routes are served `no-store` and `noindex`, and the service worker caches public static assets only — never authenticated pages or clinical API responses.
- **TLS to the database.** Production database connections require certificate-verified TLS.

**On certifications:** SANQO is pre-launch and holds no security or compliance certifications. The platform is engineered against GDPR and PDPA requirements, and we describe what is implemented rather than what is aspirational. Privacy-enhancing cryptography beyond the above is on the roadmap, not in production.

Full detail: [Access and record sharing](https://sanqo.app/docs/privacy-and-access) · [Privacy policy](https://sanqo.app/privacy-policy) · [Terms of service](https://sanqo.app/terms-of-service)

---

## The free clinic pilot

We are onboarding a small number of Malaysian clinics for a supported pilot running **January–June 2027**.

**What participating clinics get**

- Pilot software at no SANQO fee — no card required, and no automatic conversion to a paid plan
- Assisted setup, data migration support and team training
- A named onboarding contact plus 24×7 escalation for critical incidents
- An agreed transition plan: run SANQO alongside your existing system with one clear source of truth, or plan a complete replacement — your choice, decided together
- A usable handover if you leave: structured exports, with context preserved

Any third-party services or costs are discussed with you before you agree to use them.

**→ [Apply for the free clinic pilot](https://sanqo.app/join-pilot)**

Please do not include patient details in a pilot enquiry.

Before applying, the [pilot decision guide](https://sanqo.app/docs/pilot-onboarding) covers eligibility, setup, migration, training, support, how success is measured, and what your options are after June 2027.

---

## Documentation

| Guide | What it covers |
|---|---|
| [Getting started](https://sanqo.app/docs/getting-started) | Finding your workspace and how pilot onboarding works |
| [Visits and follow-ups](https://sanqo.app/docs/visits-and-follow-ups) | Checking in, sharing deliberately, arranging the next visit |
| [Access and record sharing](https://sanqo.app/docs/privacy-and-access) | Account access, guardian verification, signed sharing permissions |
| [Your free clinic pilot](https://sanqo.app/docs/pilot-onboarding) | The practical decision guide for clinic owners |
| [Migration, exports and leaving](https://sanqo.app/docs/migration-and-exit) | Bringing data in, preserving context, leaving with a clean handover |
| [Pilot support and escalation](https://sanqo.app/docs/support) | Getting help, choosing urgency, response vs. resolution |

---

## Built with

Next.js 16 (App Router) · React 19 · TypeScript · Tailwind CSS v4 · PostgreSQL · Progressive Web App

On-device face matching for patient identification runs locally in the browser via ONNX Runtime; identification models are not sent to a third-party service.

---

## Project relationships

SANQO is the clinical product at **[sanqo.app](https://sanqo.app)**.

**[eazyCare.Ai](https://www.eazycare.ai)** is the publisher: health guides, patient-facing resources, calculators and the blog live there. The two are deliberately separated — no patient records or clinical credentials are shared between them, and editorial content is never served from the clinical application.

---

## Contact

- **Clinic pilot enquiries:** [sanqo.app/join-pilot](https://sanqo.app/join-pilot)
- **Product questions and support:** [sanqo.app/docs/support](https://sanqo.app/docs/support)
- **Publisher and health resources:** [www.eazycare.ai](https://www.eazycare.ai)

---

<p align="center">
  <sub><strong>SANQO</strong> · Smart AI Navigator for Quantifiable Outcomes<br>
  AI assists the workflow. Clinicians remain responsible for clinical decisions.</sub>
</p>
