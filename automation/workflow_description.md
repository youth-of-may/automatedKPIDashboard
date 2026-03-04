# Power Automate Workflow

This document describes the automated workflow used to generate and distribute the weekly KPI briefing.

## Workflow Overview

The automation pipeline runs on a scheduled trigger and performs the following steps:

1. **Trigger**
   - Scheduled workflow runs every Monday at 8:00 AM.

2. **Refresh Dataset**
   - Power BI dataset refresh is triggered to ensure the dashboard reflects the latest data.

3. **Generate KPI Summary**
   - Key performance metrics are extracted from the dashboard.
   - Alert thresholds are evaluated for critical KPIs.

4. **Create Executive Brief**
   - A summary of the latest KPI metrics and alerts is generated.

5. **Distribution**
   - The KPI briefing is automatically posted to a Microsoft Teams channel for stakeholders.

## Benefits

- Eliminates manual reporting workflows
- Ensures consistent delivery of KPI updates
- Improves executive visibility into operational performance