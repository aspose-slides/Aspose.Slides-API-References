---
title: VerifySignature()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica la firma DSA per i dati specificati.
type: docs
weight: 14
url: /it/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) metodo

Verifica la firma [DSA](../) per i dati specificati.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) firmato con **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) firma. |

### Valore di ritorno

true - se **rgb_signature** corrisponde alla firma [DSA](../) calcolata su **rgb_hash**, altrimenti - false.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [DSA](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)