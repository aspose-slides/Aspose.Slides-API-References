---
title: SecurityPermissionFlag
second_title: Riferimento API di Aspose.Slides per C++
description: Flag di permesso di sicurezza.
type: docs
weight: 27
url: /it/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum

Flag di permesso di sicurezza.

```cpp
enum class SecurityPermissionFlag
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NoFlags | 0 | Nessun accesso. |
| Assertion | 1 | Afferma che il permesso è concesso. |
| UnmanagedCode | 2 | Chiama codice non gestito. |
| SkipVerification | 4 | Salta la verifica del codice. |
| Execution | 8 | Esegui il codice. |
| ControlThread | 16 | Esegue operazioni sui thread. |
| ControlEvidence | 32 | Controlla o modifica le evidenze CLR. |
| ControlPolicy | 64 | Visualizza e modifica la policy. |
| SerializationFormatter | 128 | Serializza. |
| ControlDomainPolicy | 256 | Imposta la policy del dominio. |
| ControlPrincipal | 512 | Controlla l'oggetto principale. |
| ControlAppDomain | 1024 | Controlla il dominio dell'applicazione. |
| RemotingConfiguration | 2048 | Configura il remoting. |
| Infrastructure | 4096 | Collega all'infrastruttura CLR. |
| BindingRedirects | 8192 | Esegue il reindirizzamento esplicito del binding. |
| AllFlags | 16383 | Senza restrizioni. |

## Vedi anche

* Spazio dei nomi [System::Security::Permissions](../)
* Libreria [Aspose.Slides](../../)