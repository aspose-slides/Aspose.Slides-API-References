---
title: HashData()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan.
type: docs
weight: 105
url: /id/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) metode


Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) untuk di hash. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte yang akan di hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritma hash. |

### Nilai Kembali

Data yang di hash.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) metode


Menghitung nilai hash dari aliran biner yang ditentukan menggunakan algoritma hash yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Aliran biner untuk di hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Algoritma hash. |

### Nilai Kembali

Data yang di hash.

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)