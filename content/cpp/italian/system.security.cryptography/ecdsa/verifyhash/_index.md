---
title: VerifyHash()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica la firma dei dati.
type: docs
weight: 118
url: /it/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) metodo

Verifica la firma dei dati.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Hash calcolato per i dati ricevuti. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Firma così ricevuta. |

### Valore di ritorno

True se la firma è valida, false altrimenti.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [ECDsa](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)