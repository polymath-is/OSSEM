# Audit Logon/Logoff

## Description

Logon/Logoff security policy settings and audit events allow you to track attempts to log on to a computer interactively or over a network. These events are particularly useful for tracking user activity and identifying potential attacks on network resources.[Microsoft Source](https://docs.microsoft.com/en-us/windows/security/threat-protection/auditing/advanced-security-audit-policy-settings#logonlogoff)

## Subcategories

| Subcategory | Description | Event Volume |
|---------|-------|---------|
| [Audit Account Lockout](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/logon_logoff/account_lockout/README.md) | Audit Account Lockout enables you to audit security events that are generated by a failed attempt to log on to an account that is locked out. | Low |
| [Audit User/Device Claims](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/logon_logoff/user_device_claims.md) | Audit User/Device Claims allows you to audit user and device claims information in the account’s logon token. Events in this subcategory are generated on the computer on which a logon session is created. For an interactive logon, the security audit event is generated on the computer that the user logged on to. | Low on a client computer. Medium on a domain controller or network servers. |
| [Audit Group Membership](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/logon_logoff/group_membership/README.md) | Audit Group Membership enables you to audit group memberships when they are enumerated on the client computer.This policy allows you to audit the group membership information in the user's logon token. Events in this subcategory are generated on the computer on which a logon session is created. | Low on a client computer. Medium on a domain controller or network servers. |
| [Audit Logoff](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/logon_logoff/logoff/README.md) | Audit Logoff determines whether the operating system generates audit events when logon sessions are terminated. | Low |
| [Audit Logon](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/logon_logoff/logon/README.md) | Audit Logon determines whether the operating system generates audit events when a user attempts to log on to a computer. | Low on a client computer. Medium on a domain controllers or network servers. |
| [Audit Other Logon/Logoff Events](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/logon_logoff/other_logon_logoff/README.md) | Audit Other Logon/Logoff Events determines whether Windows generates audit events for other logon or logoff events. | Low |
| [Audit Special Logon](https://github.com/Cyb3rWard0g/OSSEM/blob/master/data_dictionaries/windows/security/logon_logoff/special_logon/README.md) | Audit Special Logon determines whether the operating system generates audit events under special sign on (or log on) circumstances. | Low on a client computer. Medium on a domain controllers or network servers. |