---
title: VerifyHash()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica la firma dei dati.
type: docs
weight: 222
url: /it/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) metodo

Verifica la firma dei dati.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Hash calcolato per i dati ricevuti. |
| str | const [String](../../../system/string/)\& | Nome dell'algoritmo hash utilizzato. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Firma così ricevuta. |

### Valore di ritorno

True se la firma è valida, false altrimenti.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) metodo

Verifica che la firma dell'hash specificato sia valida.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
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
* Classe [String](../../../system/string/)
* Classe [RSACryptoServiceProvider](../)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)