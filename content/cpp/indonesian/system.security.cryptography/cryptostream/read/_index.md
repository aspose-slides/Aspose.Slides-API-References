---
title: Read()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca data dari aliran.
type: docs
weight: 14
url: /id/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Membaca data dari aliran.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer data tujuan. |
| offset | **int32_t** | Offset dalam buffer tujuan. |
| count | **int32_t** | Jumlah byte yang akan dibaca. |

### Nilai Kembalian

Jumlah byte yang sebenarnya dibaca.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode

Membaca data dari aliran.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Buffer data tujuan. |
| offset | **int32_t** | Offset dalam buffer tujuan. |
| count | **int32_t** | Jumlah byte yang akan dibaca. |

### Nilai Kembalian

Jumlah byte yang sebenarnya dibaca.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)