---
title: VerifyData()
second_title: Referensi API Aspose.Slides untuk C++
description: Memeriksa tanda tangan data.
type: docs
weight: 209
url: /id/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) metode

Memeriksa tanda tangan data.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) untuk memeriksa tanda tangan. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Tanda tangan seperti yang diterima. |

### Nilai Kembalian

True if signature is valid, false otherwise.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metode

Memverifikasi bahwa tanda tangan data yang ditentukan valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data yang ditandatangani. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan true jika tanda tangan valid, selainnya - false. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) metode

Memverifikasi bahwa tanda tangan data yang ditentukan valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data yang ditandatangani. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte untuk di-hash. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan true jika tanda tangan valid, selainnya - false. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) metode

Memverifikasi bahwa tanda tangan aliran biner yang ditentukan valid.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Data yang ditandatangani. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Data tanda tangan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan true jika tanda tangan valid, selainnya - false. |

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)