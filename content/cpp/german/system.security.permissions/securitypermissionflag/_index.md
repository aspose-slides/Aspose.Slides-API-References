---
title: SecurityPermissionFlag
second_title: Aspose.Slides für C++ API-Referenz
description: Flags der Sicherheitsberechtigung.
type: docs
weight: 27
url: /de/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag Enum

Flags der Sicherheitsberechtigung.

```cpp
enum class SecurityPermissionFlag
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| NoFlags | 0 | Kein Zugriff. |
| Assertion | 1 | Bestätigen, dass die Berechtigung erteilt wurde. |
| UnmanagedCode | 2 | Unverwalteten Code aufrufen. |
| SkipVerification | 4 | Codeüberprüfung überspringen. |
| Execution | 8 | Code ausführen. |
| ControlThread | 16 | Operationen auf Threads durchführen. |
| ControlEvidence | 32 | CLR-Evidence steuern oder ändern. |
| ControlPolicy | 64 | Richtlinie anzeigen und ändern. |
| SerializationFormatter | 128 | Serialisieren. |
| ControlDomainPolicy | 256 | Domainrichtlinie festlegen. |
| ControlPrincipal | 512 | Principal-Objekt steuern. |
| ControlAppDomain | 1024 | Anwendungsdomäne steuern. |
| RemotingConfiguration | 2048 | Remoting konfigurieren. |
| Infrastructure | 4096 | In die CLR-Infrastruktur einbinden. |
| BindingRedirects | 8192 | Explizite Bindungsumleitung ausführen. |
| AllFlags | 16383 | Uneingeschränkt. |

## Siehe auch

* Namensraum [System::Security::Permissions](../)
* Bibliothek [Aspose.Slides](../../)