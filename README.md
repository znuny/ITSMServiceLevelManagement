<div align="center">
  <a href="https://www.znuny.org">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://www.znuny.com/assets/znuny-logo.svg">
      <img alt="Znuny" src="https://www.znuny.com/assets/znuny-logo-black.svg" width="300">
    </picture>
  </a>

  ![Build status](https://badge.proxy.znuny.com/ITSMServiceLevelManagement/rel-7_3)
</div>

ITSM Service Level Management
=============================

**Feature List**

This package provides ITSM Service Level Management (SLM) for Znuny. It extends the ITSM stack with statistics and reports to monitor and report on service levels.

- **Ticket Statistics**: Predefined reports for ticket-based SLA and service metrics (e.g. ticket overview, resolution times)
- **Configuration Item Statistics**: Reports on configuration items for asset and CI-related KPIs
- **First-Level Solution Rate**: Statistics for first-level solution rate (e.g. by queue, service, time range)
- **Solution Time Average**: Statistics for average ticket solution time
- **Change Management Statistics**: Reports on changes for change-related service level analysis

Statistics are available in the Statistics module and can be used for dashboards, reports and SLA monitoring. The package registers its stat definitions on install and makes them available to agents with the appropriate permissions.

**Prerequisites**

- Znuny 7.3
- ITSMCore 7.3.1

**Installation**

Install via Admin interface → Package Manager. The package is part of the Znuny ITSM stack and can be installed from the Znuny repository or from a built .opm file. Install after ITSMCore (and optionally after ITSM Change Management and ITSM Configuration Management for full stat coverage).

**Configuration**

No separate admin UI; stat definitions are registered by the package. Use Statistics in the agent interface to run and configure the ITSM stats. Access is subject to the usual statistics and report permissions.

**Download**

Source code is available in the [ITSMServiceLevelManagement repository](https://download.znuny.org/releases/itsm/latest/). For packaged releases, use the Znuny package repository or build from source.

**Commercial Support**

For this extension and for Znuny in general visit [www.znuny.com](https://www.znuny.com). Looking forward to hear from you!

Enjoy!

Your Znuny Team!

[www.znuny.com](https://www.znuny.com)
