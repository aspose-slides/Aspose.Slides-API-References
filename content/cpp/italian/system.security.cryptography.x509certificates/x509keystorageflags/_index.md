---
title: X509KeyStorageFlags
second_title: Riferimento API Aspose.Slides per C++
description: Definisce come memorizzare la chiave.
type: docs
weight: 261
url: /it/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum

Definisce come memorizzare la chiave.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| DefaultKeySet | 0 | Utilizza il set di chiavi predefinito. |
| UserKeySet | 1 | Utilizza l'archivio associato all'utente invece di quello locale della macchina. |
| MachineKeySet | 2 | Utilizza l'archivio locale della macchina invece di quello dell'utente. |
| Exportable | 4 | Segna le chiavi importate come esportabili. |
| UserProtected | 8 | Notifica all'utente che la chiave è in uso. |
| PersistKeySet | 16 | La chiave viene mantenuta quando si importa il certificato. |

## Vedi anche

* Spazio dei nomi [System::Security::Cryptography::X509Certificates](../)
* Libreria [Aspose.Slides](../../)