---
title: HashData()
second_title: Referencja API Aspose.Slides dla C++
description: Oblicza wartość skrótu określonej tablicy danych przy użyciu podanego algorytmu skrótu.
type: docs
weight: 105
url: /pl/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) metoda


Oblicza wartość skrótu podanej tablicy danych przy użyciu określonego algorytmu skrótu.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) do skrótu. |
| offset | **int32_t** | Offset w **data**. |
| count | **int32_t** | Liczba bajtów do skrótu. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algorytm skrótu. |

### Wartość zwracana

Hashed data.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) metoda


Oblicza wartość skrótu określonego strumienia binarnego przy użyciu określonego algorytmu skrótu.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Strumień binarny do skrótu. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algorytm skrótu. |

### Wartość zwracana

Hashed data.

## Zobacz także

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Klasa [ECDsaBotan](../)
* Struktura [HashAlgorithmName](../../hashalgorithmname/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)