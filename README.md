# Practo Clinic Appointment Follow-up Analyzer

## Overview

This project is a Google Colab based clinic operations analysis system.

It combines appointment, patient, doctor, follow-up, complaint, service ticket, and doctor availability data to identify operational issues and prioritize patient-support cases.

## Key Features

- Multi-file loading
- Data validation
- Data cleaning
- Missed appointment detection
- Doctor availability analysis
- Follow-up SLA analysis
- Complaint analysis
- Service ticket analysis
- Duplicate and anomaly detection
- Appointment-level master table
- Priority classification
- Patient Impact Score
- Recommended actions
- AI-ready support prompts
- Patient search
- Operational filters
- Management summaries
- CSV report exports
- Debug logging

## Technologies

- Python
- Pandas
- Google Colab
- CSV
- Excel
- JSON
- TXT
- ipywidgets

## How to Run

1. Open the notebook in Google Colab.
2. Run the notebook from top to bottom.
3. Upload the required datasets when prompted.
4. Review validation output.
5. Run the analysis sections.
6. Use the search and filtering interface.
7. Review generated reports.
8. Export CSV reports if required.

## Input Files

- appointments.csv
- patients.csv
- doctors.csv
- doctor_availability.csv
- followups.xlsx
- patient_complaints.json
- service_tickets.csv
- clinic_notes.txt

## Output

The notebook generates:
- appointment master report
- validation report
- anomaly report
- doctor summary
- city summary
- patient summary
- follow-up report
- complaint report
- ticket report
- priority queue
- AI-ready prompt report
- debug log

## Project Scope

This is an educational and simulated clinic operations project.

It does not connect to a real Practo production environment or real patient systems.
