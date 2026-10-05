# BhoomiGuard — SIH Prototype

A polished Smart India Hackathon prototype for **SIH26018 — Intelligent Land Record Digitization and Validation System**.

## Run locally

```bash
npm install
npm run dev
```

Open http://localhost:3000

## Demo

The app works without Supabase, OCR APIs, GIS APIs, or blockchain infrastructure. It uses realistic fictional demo data and simulated processing so the complete journey is reliable for judging.

Demo flow:

Login → Dashboard → Upload Record → OCR Extraction → Validation → GIS Map → Officer Review → Audit Trail

## Supabase-ready

`.env.example` contains the future Supabase variables. The prototype intentionally falls back to in-memory/local demo data when they are not configured.

## Source basis

The screens and workflow are based on the BhoomiGuard SIH deck: upload scanned record, OCR extraction, AI cleaning/structuring, GIS/database cross-check, discrepancy detection, officer review, digital approval and blockchain audit trail.
