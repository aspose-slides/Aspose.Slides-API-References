---
title: VerifyData()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica che la firma dei dati specificati sia valida.
type: docs
weight: 157
url: /it/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodo


Verifica che la firma dei dati specificati sia valida.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati firmati. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modalità di padding. restituisce true se la firma è valida, altrimenti - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodo


Verifica che la firma dei dati specificati sia valida.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati firmati. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da hashare. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modalità di padding. restituisce true se la firma è valida, altrimenti - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodo


Verifica che la firma del flusso binario specificato sia valida.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Dati firmati. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Dati della firma. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modalità di padding. restituisce true se la firma è valida, altrimenti - false. |

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)