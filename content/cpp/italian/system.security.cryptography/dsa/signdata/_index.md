---
title: SignData()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo hash specificato e firma il risultato.
type: docs
weight: 79
url: /it/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metodo

Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo hash specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array di dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. restituisce [DSA](../) firma per i dati di input. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metodo

Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo hash specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array di dati di input. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da utilizzare come dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. restituisce [DSA](../) firma per i dati di input. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) metodo

Calcola il valore hash del flusso binario specificato utilizzando l'algoritmo hash specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flusso binario. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo hash. restituisce [DSA](../) firma per i dati di input. |

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Classe [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)