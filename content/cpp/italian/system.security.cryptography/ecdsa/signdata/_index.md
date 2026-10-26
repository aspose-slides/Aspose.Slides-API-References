---
title: SignData()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola il valore hash dell'array di dati specificato usando l'algoritmo hash specificato e firma il risultato.
type: docs
weight: 79
url: /it/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo di hash specificato e firma il risultato.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array di dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. restituisce la firma ECDSA per i dati di input. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo di hash specificato e firma il risultato.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array di dati di input. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da usare come dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. restituisce la firma ECDSA per i dati di input. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


Calcola il valore hash del flusso binario specificato utilizzando l'algoritmo di hash specificato e firma il risultato.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flusso binario. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. restituisce la firma ECDSA per i dati di input. |

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)