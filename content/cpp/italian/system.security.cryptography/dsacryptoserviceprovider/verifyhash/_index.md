---
title: VerifyHash()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica la firma dei dati.
type: docs
weight: 222
url: /it/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method

Verifica la firma dei dati.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash calcolato per i dati ricevuti. |
| str | const [String](../../../system/string/)\& | Nome dell'algoritmo di hash utilizzato. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Firma così ricevuta. |

### Valore restituito

Vero se la firma è valida, falso altrimenti.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [String](../../../system/string/)
* Classe [DSACryptoServiceProvider](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)