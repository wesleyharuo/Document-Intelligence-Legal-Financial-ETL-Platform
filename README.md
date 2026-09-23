# Document-Intelligence-Legal-Financial-ETL-Platform
Project Overview
Development of an automated ingestion and processing engine designed for unstructured financial and legal documents, including invoices, receipts, and reports. The solution eliminates manual bottlenecks in data extraction, ensuring accounting compliance and accelerating financial closing cycles.

Business Challenge
Accounting firms and legal practices handle high volumes of heterogeneous documents (PDFs, images, and legacy spreadsheets). Manual data entry and reconciliation lead to human error, consume extensive operational hours, and delay the delivery of managerial and tax reports.

Technical Architecture & Implementation
-Ingestion and Intelligent Parsing: Built a Python-based pipeline integrated with Large Language Models (LLMs) to read, classify, and automatically extract key fields (such as tax IDs, amounts, taxes, and cost centers).
-Validation and Loading (ETL): Implemented data consistency routines that cross-reference extracted information with relational databases (SQLite/PostgreSQL) prior to feeding ERP or accounting systems.
-Workflow Orchestration: Configured low-code workflows using n8n to trigger discrepancy alerts and systematically organize digitized files into secure repositories.

Key Technologies Used   
-Languages & Libraries: Python, Pandas, SQL
-Databases: SQLite, PostgreSQL
-Tools & Orchestration: n8n, LLM Prompt Engineering, REST APIs

Results and Impact
-Achieved an 80% reduction in time spent on manual data entry.
-Significantly mitigated human error in tax and accounting entries.
-Accelerated the delivery of trial balances and audit reports to clients.
