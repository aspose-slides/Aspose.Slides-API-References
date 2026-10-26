---
title: VerifyData()
second_title: Referensi API Aspose.Slides untuk C++
description: Memverifikasi bahwa tanda tangan data yang ditentukan valid.
type: docs
weight: 92
url: /id/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Memverifikasi bahwa tanda tangan data yang ditentukan valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data yang ditandatangani. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Memverifikasi bahwa tanda tangan data yang ditentukan valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data yang ditandatangani. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte yang akan di-hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan true jika tanda tangan valid, jika tidak - false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Memverifikasi bahwa tanda tangan aliran biner yang ditentukan valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
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
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)