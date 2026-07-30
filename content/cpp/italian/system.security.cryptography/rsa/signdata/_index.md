---
title: SignData()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola il valore hash dell'array di dati specificato usando l'algoritmo hash e il padding specificati, e firma il risultato.
type: docs
weight: 131
url: /it/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodo

Calcola il valore hash dell'array di dati specificato usando l'algoritmo hash e il padding specificati, e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array di dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modalità di padding. restituisce la firma [RSA](../) per i dati di input. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodo

Calcola il valore hash dell'array di dati specificato usando l'algoritmo hash e il padding specificati, e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array di dati di input. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da usare come dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modalità di padding. restituisce la firma [RSA](../) per i dati di input. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) metodo

Calcola il valore hash dello stream binario specificato usando l'algoritmo hash e il padding specificati, e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Stream binario. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Modalità di padding. restituisce la firma [RSA](../) per i dati di input. |

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [RSASignaturePadding](../../rsasignaturepadding/)
* Classe [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)