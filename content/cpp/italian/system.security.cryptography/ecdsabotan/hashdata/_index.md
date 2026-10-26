---
title: HashData()
second_title: Riferimento API Aspose.Slides per C++
description: Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo hash specificato.
type: docs
weight: 105
url: /it/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) metodo


Calcola il valore hash dell'array di dati specificato utilizzando l'algoritmo hash specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) da hashare. |
| offset | **int32_t** | Offset in **data**. |
| count | **int32_t** | Numero di byte da hashare. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo hash. |

### Valore di ritorno

Dati hashati.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) metodo


Calcola il valore hash del flusso binario specificato utilizzando l'algoritmo hash specificato.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Flusso binario da hashare. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritmo hash. |

### Valore di ritorno

Dati hashati.

## Vedi anche

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)