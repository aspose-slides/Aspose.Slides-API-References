---
title: SignData()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola il valore hash dell'array di dati specificato e firma il risultato.
type: docs
weight: 131
url: /it/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) metodo

Calcola il valore hash dell'array di dati specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. restituisce la firma ECDSA per i dati di input. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) metodo

Calcola il valore hash dell'array di dati specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da utilizzare come dati di input. restituisce la firma ECDSA per i dati di input. |

## ECDsaBotan::SignData(const StreamPtr\&) metodo

Calcola il valore hash del flusso binario specificato e firma il risultato.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Flusso binario. restituisce la firma ECDSA per i dati di input. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metodo

Calcola il valore hash dell'array di dati specificato usando l'algoritmo di hash specificato e firma il risultato.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. restituisce la firma ECDSA per i dati di input. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metodo

Calcola il valore hash dell'array di dati specificato usando l'algoritmo di hash specificato e firma il risultato.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Input data array. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da utilizzare come dati di input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritmo di hash. restituisce la firma ECDSA per i dati di input. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) metodo

Calcola il valore hash del flusso binario specificato usando l'algoritmo di hash specificato e firma il risultato.

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
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)