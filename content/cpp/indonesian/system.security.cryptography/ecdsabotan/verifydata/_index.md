---
title: VerifyData()
second_title: Referensi API Aspose.Slides untuk C++
description: Memverifikasi bahwa tanda tangan data yang ditentukan valid.
type: docs
weight: 170
url: /id/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) metode

Memverifikasi bahwa tanda tangan data yang ditentukan valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data yang ditandatangani. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) metode

Memverifikasi bahwa tanda tangan data yang ditentukan valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data yang ditandatangani. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte untuk di-hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) metode

Memverifikasi bahwa tanda tangan aliran biner yang ditentukan valid.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Data yang ditandatangani. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metode

Memverifikasi bahwa tanda tangan data yang ditentukan valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data yang ditandatangani. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metode

Memverifikasi bahwa tanda tangan data yang ditentukan valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data yang ditandatangani. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte untuk di-hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metode

Memverifikasi bahwa tanda tangan aliran biner yang ditentukan valid.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Data yang ditandatangani. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Kelas [ECDsaBotan](../)
* Struktur [HashAlgorithmName](../../hashalgorithmname/)
* Ruang Nama [System::Security::Cryptography](../../)
* Pustaka [Aspose.Slides](../../../)