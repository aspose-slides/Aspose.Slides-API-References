---
title: SignData()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung tanda tangan untuk nilai masukan yang ditentukan.
type: docs
weight: 183
url: /id/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) metode

Menghitung tanda tangan untuk nilai masukan yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) untuk membaca data input dari. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algoritma hash yang akan digunakan. |

### Nilai Kembali

[RSA](../../rsa/) tanda tangan untuk data yang ditentukan.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) metode

Menghitung tanda tangan untuk nilai masukan yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Aliran untuk membaca data yang akan ditandatangani. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algoritma hash yang akan digunakan. |

### Nilai Kembali

[RSA](../../rsa/) tanda tangan untuk data yang ditentukan.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) metode

Menghitung tanda tangan untuk nilai masukan yang ditentukan.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) untuk membaca data input dari. |
| offset | **int32_t** | Indeks awal irisan buffer masukan. |
| count | **int32_t** | Ukuran irisan buffer masukan. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Algoritma hash yang akan digunakan. |

### Nilai Kembali

[RSA](../../rsa/) tanda tangan untuk data yang ditentukan.

## Lihat Juga

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Object](../../../system/object/)
* Kelas [RSACryptoServiceProvider](../)
* Kelas [Stream](../../../system.io/stream/)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)