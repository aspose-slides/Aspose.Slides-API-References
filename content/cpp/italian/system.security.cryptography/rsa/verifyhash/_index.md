---
title: VerifyHash()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica che la firma dell'hash specificato sia valida.
type: docs
weight: 170
url: /it/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metodo


Verifica che la firma dell'hash specificato sia valida.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Valore hash dei dati firmati. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Dati della firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Modalità di padding. restituisce true se la firma è valida, altrimenti - false. |

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)