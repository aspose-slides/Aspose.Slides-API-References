---
title: SignData()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung nilai hash dari array data yang ditentukan, dan menandatangani hasilnya.
type: docs
weight: 131
url: /id/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) method

Menghitung nilai hash dari array data yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array data masukan. Mengembalikan tanda tangan ECDSA untuk data masukan. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) method

Menghitung nilai hash dari array data yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array data masukan. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte yang digunakan sebagai data masukan. Mengembalikan tanda tangan ECDSA untuk data masukan. |

## ECDsaBotan::SignData(const StreamPtr\&) method

Menghitung nilai hash dari aliran biner yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aliran biner. Mengembalikan tanda tangan ECDSA untuk data masukan. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array data masukan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. Mengembalikan tanda tangan ECDSA untuk data masukan. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array data masukan. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte yang digunakan sebagai data masukan. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. Mengembalikan tanda tangan ECDSA untuk data masukan. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

Menghitung nilai hash dari aliran biner yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aliran biner. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. Mengembalikan tanda tangan ECDSA untuk data masukan. |

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Kelas [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)