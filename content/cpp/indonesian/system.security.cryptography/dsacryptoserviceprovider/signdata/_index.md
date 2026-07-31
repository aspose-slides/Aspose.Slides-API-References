---
title: SignData()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung tanda tangan dari nilai input yang ditentukan.
type: docs
weight: 183
url: /id/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) metode

Menghitung tanda tangan dari nilai input yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) untuk membaca data input dari. |

### Nilai Kembalian

[DSA](../../dsa/) tanda tangan untuk data yang ditentukan.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) metode

Menghitung tanda tangan dari nilai input yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran untuk membaca data yang ditandatangani dari. |

### Nilai Kembalian

[DSA](../../dsa/) tanda tangan untuk data yang ditentukan.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) metode

Menghitung tanda tangan dari nilai input yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) untuk membaca data input dari. |
| offset | **int32_t** | Indeks awal irisan buffer input. |
| count | **int32_t** | Ukuran irisan buffer input. |

### Nilai Kembalian

[DSA](../../dsa/) tanda tangan untuk data yang ditentukan.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) metode

Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array data input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan [DSA](../../dsa/) tanda tangan untuk data input. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) metode

Menghitung nilai hash dari array data yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Array data input. |
| offset | **int32_t** | Offset dalam **data**. |
| count | **int32_t** | Jumlah byte yang digunakan sebagai data input. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan [DSA](../../dsa/) tanda tangan untuk data input. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) metode

Menghitung nilai hash dari aliran biner yang ditentukan menggunakan algoritma hash yang ditentukan, dan menandatangani hasilnya.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Aliran biner. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Algoritma hash. mengembalikan [DSA](../../dsa/) tanda tangan untuk data input. |

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Kelas [DSACryptoServiceProvider](../)
* Kelas [Stream](../../../system.io/stream/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Ruang nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)