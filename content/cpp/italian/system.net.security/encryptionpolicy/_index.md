---
title: EncryptionPolicy
second_title: Riferimento API Aspose.Slides per C++
description: Elenca le politiche di crittografia.
type: docs
weight: 53
url: /it/system.net.security/encryptionpolicy/
---
## EncryptionPolicy enum

Elenca le politiche di crittografia.

```cpp
enum class EncryptionPolicy
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| RequireEncryption | 0 | Richiede la crittografia e non consente mai un cifrario 'Null'. |
| AllowNoEncryption | 1 | Preferisce l'uso della crittografia completa ma può essere usato un cifrario 'Null' se il server è d'accordo. |
| NoEncryption | 2 | Consente di non usare la crittografia e richiede che sia usato un cifrario 'Null' se l'altro endpoint può gestire un cifrario 'Null'. |

## Vedi anche

* Namespace [System::Net::Security](../)
* Libreria [Aspose.Slides](../../)