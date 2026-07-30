---
title: HashData()
second_title: Aspose.Slides pro C++ API Reference
description: Vypočítá hash hodnotu zadaného pole dat pomocí určeného hash algoritmu.
type: docs
weight: 105
url: /cs/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) metoda


Vypočítá hash hodnotu specifikovaného pole dat pomocí specifikovaného hash algoritmu.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) k zahashování. |
| offset | **int32_t** | Posun v **data**. |
| count | **int32_t** | Počet bajtů k zahashování. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algoritmus. |

### Návratová hodnota

Zahashovaná data.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) metoda


Vypočítá hash hodnotu zadaného binárního proudu pomocí specifikovaného hash algoritmu.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Binární proud k zahashování. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algoritmus. |

### Návratová hodnota

Zahashovaná data.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)