---
title: HashData()
second_title: Aspose.Slides C++ API Referenciája
description: A megadott adat tömb hash értékét a megadott hash algoritmus használatával számítja ki.
type: docs
weight: 105
url: /hu/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) metódus


A megadott adat tömb hash értékét számítja ki a megadott hash algoritmus használatával.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) a hash-hez. |
| offset | **int32_t** | Az **data** eltolása. |
| count | **int32_t** | A hash-hez felhasználandó bájtok száma. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algoritmus. |

### Visszatérési érték

Hasholt adat.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) metódus


A megadott bináris adatfolyam hash értékét számítja ki a megadott hash algoritmus használatával.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Hash-olandó bináris adatfolyam. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Hash algoritmus. |

### Visszatérési érték

Hasholt adat.

## Lásd még

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)