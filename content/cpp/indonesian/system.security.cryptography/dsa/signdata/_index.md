---
title: SignData()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.
type: docs
weight: 79
url: /id/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metode

Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array data masukan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. Mengembalikan tanda tangan [DSA](../) untuk data masukan. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metode

Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array data masukan. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte yang digunakan sebagai data masukan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. Mengembalikan tanda tangan [DSA](../) untuk data masukan. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) metode

Menghitung nilai hash dari aliran biner yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aliran biner. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. Mengembalikan tanda tangan [DSA](../) untuk data masukan. |

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Kelas [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)