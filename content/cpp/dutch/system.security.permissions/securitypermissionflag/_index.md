---
title: SecurityPermissionFlag
second_title: Aspose.Slides for C++ API-referentie
description: Vlaggen van beveiligingsmachtiging.
type: docs
weight: 27
url: /nl/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Vlaggen van beveiligingsmachtiging.

```cpp
enum class SecurityPermissionFlag
```

### Waarden

| Name | Value | Description |
| --- | --- | --- |
| NoFlags | 0 | Geen toegang. |
| Assertion | 1 | Beweren dat toestemming is verleend. |
| UnmanagedCode | 2 | Niet-beheerde code aanroepen. |
| SkipVerification | 4 | Code-verificatie overslaan. |
| Execution | 8 | Code uitvoeren. |
| ControlThread | 16 | Operaties op threads uitvoeren. |
| ControlEvidence | 32 | CLR-bewijs beheren of wijzigen. |
| ControlPolicy | 64 | Beleid bekijken en wijzigen. |
| SerializationFormatter | 128 | Serialiseren. |
| ControlDomainPolicy | 256 | Domeinbeleid instellen. |
| ControlPrincipal | 512 | Principal-object beheren. |
| ControlAppDomain | 1024 | Applicatiedomein beheren. |
| RemotingConfiguration | 2048 | Remoting configureren. |
| Infrastructure | 4096 | Aansluiten op CLR-infrastructuur. |
| BindingRedirects | 8192 | Expliciete binding-omleiding uitvoeren. |
| AllFlags | 16383 | Onbeperkt. |

## Zie ook

* Naamruimte [System::Security::Permissions](../)
* Bibliotheek [Aspose.Slides](../../)