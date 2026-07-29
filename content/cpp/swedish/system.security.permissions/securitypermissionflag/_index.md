---
title: SecurityPermissionFlag
second_title: Aspose.Slides för C++ API-referens
description: Flaggor för säkerhetsbehörighet.
type: docs
weight: 27
url: /sv/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

Flaggor för säkerhetsbehörighet.

```cpp
enum class SecurityPermissionFlag
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| NoFlags | 0 | Ingen åtkomst. |
| Assertion | 1 | Påstå att behörigheten är beviljad. |
| UnmanagedCode | 2 | Anropa ohanterad kod. |
| SkipVerification | 4 | Hoppa över kodverifiering. |
| Execution | 8 | Kör kod. |
| ControlThread | 16 | Utföra operationer på trådar. |
| ControlEvidence | 32 | Kontrollera eller ändra CLR-bevis. |
| ControlPolicy | 64 | Visa och ändra policy. |
| SerializationFormatter | 128 | Serialisera. |
| ControlDomainPolicy | 256 | Ställ in domänpolicy. |
| ControlPrincipal | 512 | Kontrollera principal-objekt. |
| ControlAppDomain | 1024 | Kontrollera programdomän. |
| RemotingConfiguration | 2048 | Konfigurera remoting. |
| Infrastructure | 4096 | Anslut till CLR-infrastruktur. |
| BindingRedirects | 8192 | Utföra explicit bindningsomdirigering. |
| AllFlags | 16383 | Obegränsad. |

## Se även

* Namnrymd [System::Security::Permissions](../)
* Bibliotek [Aspose.Slides](../../)