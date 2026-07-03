<div align="center">

# AI-Powered Customer Support & Service Automation

### Salesforce Service Cloud | Flows | Prompt Builder | Reports | Dashboards

*A Salesforce-based intelligent customer support automation system developed for an Electronics & Gadgets company.*

![Salesforce](https://img.shields.io/badge/Salesforce-Service%20Cloud-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white)
![Prompt Builder](https://img.shields.io/badge/Prompt-Builder-0176D3?style=for-the-badge)
![Flow](https://img.shields.io/badge/Record%20Triggered-Flows-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</div>

---

# Project Overview

The **AI-Powered Customer Support & Service Automation** system is developed using **Salesforce Service Cloud** to automate customer support operations for an international Electronics & Gadgets company.

The application centralizes customer support by managing customers, products, orders, and support cases while automating workflows using Salesforce Flows, Queues, Validation Rules, Approval Processes, and AI-powered summaries with **Prompt Builder**.

---

# Key Features

### Customer Management

- Customer Information
- Contact Details
- Customer Type
- Country Information

### Product Management

- Product Catalog
- Categories
- Pricing
- Warranty Information
- Stock Management

### Order Management

- Order Tracking
- Customer Lookup
- Product Lookup
- Order Status
- Total Amount

### User Case Management

- Issue Tracking
- Priority Management
- Status Tracking
- Resolution Details
- AI Summary Generation

### Automation

- Record Triggered Flows
- Queue-Based Assignment
- Approval Workflow
- Validation Rules

### AI Features

- Salesforce Prompt Builder
- AI Summary Generation
- Intelligent Customer Support Assistance

### Analytics

- Reports
- Dashboards
- Support Insights

---

# System Architecture

```text
Customer
    │
    ▼
Order
    │
    ▼
Product
    │
    ▼
User Case
    │
    ├── Validation Rules
    ├── Record Triggered Flow
    ├── Queues
    ├── Approval Process
    └── Prompt Builder
```

---

# Data Model

## Customer

- Customer Name
- Email
- Phone
- Country
- Customer Type

## Product

- Product Name
- Category
- Price
- Warranty Expiry
- Stock Quantity

## Order

- Order Number
- Customer
- Product
- Order Date
- Status
- Total Amount

## User Case

- Case Number
- Customer
- Product
- Order
- Issue Type
- Priority
- Status
- Description
- Resolution
- AI Summary

---

# Salesforce Automation

### Validation Rules

- Description required for Critical cases
- Product required for Warranty cases
- Resolution required before closing cases

### Record Triggered Flow

- Processes newly created User Cases
- Automates business logic
- Updates records automatically

### Queues

- Damage Support Queue
- Warranty Support Queue
- Order Support Queue

### Approval Process

- Critical support cases
- Automated approval workflow

---

# AI Integration

Salesforce **Prompt Builder** is used to generate professional AI summaries for customer support cases.

The generated summary includes:

- Case Information
- Issue Description
- Priority
- Current Status

---

# Reports & Dashboard

### Reports

- User Cases by Status
- Orders by Status
- Products by Category

### Dashboard

**Customer Support Dashboard**

Displays:

- Case Status Distribution
- Order Status Overview
- Product Category Distribution

---

# Security

The application implements:

- System Administrator Profile
- Object-Level Security
- Field-Level Security
- Queue Membership

---

# 📂 Repository Structure

```text
 Smartbridge-Salesforce-AI-Powered-Customer-Support
│
├── 📄 README.md
├── 📁 Documentation
├── 📁 Salesforce-Setup
├── 📁 Screenshots
```

---

# Technologies Used

| Technology | Purpose |
|------------|----------|
| Salesforce Service Cloud | CRM Platform |
| Lightning App Builder | UI Development |
| Flow Builder | Process Automation |
| Prompt Builder | AI Integration |
| Validation Rules | Data Validation |
| Reports | Analytics |
| Dashboards | Visualization |

---

# Author

**Poojith Varma**

</div>
