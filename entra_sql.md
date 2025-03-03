---
parent: SQL Docs
title: Configure Entra ID for SQL Server 2022 and up
---

# Prerequisites
*   Follow the [Microsoft documentation]

# Process

{: .warning }
Even though Microsoft states the chosen admin user will be granted the sysadmin role in SQL, the behavior appears to be inconsistent

1.  Create two Entra security groups using the following naming convention:
  *   TIG-Foortified-Cloud-SQL-Admins
  *   TIG-Foortified-Cloud-SQL-Users

[Microsoft documentation]: https://learn.microsoft.com/en-us/sql/relational-databases/security/authentication-access/azure-ad-authentication-sql-server-setup-tutorial?view=sql-server-ver16
