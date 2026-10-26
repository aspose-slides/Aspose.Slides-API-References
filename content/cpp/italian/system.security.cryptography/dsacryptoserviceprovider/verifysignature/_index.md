---
title: VerifySignature()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica la firma DSA per i dati specificati.
type: docs
weight: 118
url: /it/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) metodo

Verifica la firma [DSA](../../dsa/) per i dati specificati.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) firmata con **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) firma. |

### Valore di ritorno

true - se **rgb_signature** corrisponde alla [DSA](../../dsa/) firma calcolata su **rgb_hash**, altrimenti - false.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Classe [DSACryptoServiceProvider](../)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)