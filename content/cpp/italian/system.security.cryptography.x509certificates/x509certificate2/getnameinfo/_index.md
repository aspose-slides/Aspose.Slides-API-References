---
title: GetNameInfo()
second_title: Riferimento API Aspose.Slides per C++
description: Ottiene il nome del soggetto o dell'emittente dal certificato.
type: docs
weight: 248
url: /it/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method

Ottiene il nome del soggetto o dell'emittente dal certificato.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Arguments

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Opzioni di formattazione del nome. |
| for_issuer | **bool** | Se true, restituisce il nome dell'emittente, altrimenti restituisce il nome del soggetto. |

### Valore di ritorno

Nome dell'emittente o del soggetto formattato.

## Vedi anche

* Enum [X509NameType](../../x509nametype/)
* Classe [String](../../../system/string/)
* Classe [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Libreria [Aspose.Slides](../../../)