Sitemap and User Flow
Smart Poultry Care Management System

1. Sitemap

The sitemap shows the pages and navigation structure of the Smart Poultry Care Management System.

mermaid
flowchart TD
    A[Login Page] --> B[Dashboard]

    B --> C[Farm Management]
    B --> D[Flock Management]
    B --> E[Feed Management]
    B --> F[Feeding Schedule]
    B --> G[Vaccination Records]
    B --> H[Egg Production]
    B --> I[Expense Management]
    B --> J[Reminders]

    C --> K[Add / Edit Farm]
    D --> L[Add / Edit Flock]
    E --> M[Add / Edit Feed]
    F --> N[Add / Edit Schedule]
    G --> O[Add / Edit Vaccination]
    H --> P[Add / Edit Production]
    I --> Q[Add / Edit Expense]
    J --> R[Add / Edit Reminder]


2. User Flow

This user flow shows how a farm owner uses the application to record daily egg production.

mermaid
flowchart TD
    A([Start]) --> B[Open Web Application]
    B --> C[Login]
    C --> D[View Dashboard]
    D --> E[Open Egg Production Page]
    E --> F[Click Add Production]
    F --> G[Enter Production Details]
    G --> H{Are the details correct?}
    H -->|No| G
    H -->|Yes| I[Save Record]
    I --> J[View Updated Production Records]
    J --> K([End])


3. Explanation

The sitemap presents the main pages of the Smart Poultry Care Management System and their corresponding management pages.

The user flow demonstrates how a farm owner records daily egg production. The user logs in, opens the dashboard, navigates to the egg production page, enters the production details, checks the information, and saves the record.

These diagrams help explain the website structure and how users interact with the system.
