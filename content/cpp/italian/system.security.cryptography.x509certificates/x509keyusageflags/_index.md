---
title: X509KeyUsageFlags
second_title: Riferimento API Aspose.Slides per C++
description: Definisce come può essere usata la chiave del certificato.
type: docs
weight: 274
url: /it/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags enum

Definisce come può essere usata la chiave del certificato.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | 0 | Nessun parametro di utilizzo della chiave. |
| EncipherOnly | 1 | La chiave può essere usata solo per la cifratura. |
| CrlSign | 2 | La chiave può essere usata per firmare una lista di revoca dei certificati. |
| KeyCertSign | 4 | La chiave può essere usata per firmare certificati. |
| KeyAgreement | 8 | La chiave può essere usata per determinare l'accordo di chiave. |
| DataEncipherment | 16 | La chiave può essere usata per la cifratura dei dati. |
| KeyEncipherment | 32 | La chiave può essere usata per la cifratura della chiave. |
| NonRepudiation | 64 | La chiave può essere usata per l'autenticazione. |
| DigitalSignature | 128 | La chiave può essere usata come firma digitale. |
| DecipherOnly | 32768 | La chiave può essere usata solo per la decifratura. |

## Vedi anche

* Spazio dei nomi [System::Security::Cryptography::X509Certificates](../)
* Libreria [Aspose.Slides](../../)