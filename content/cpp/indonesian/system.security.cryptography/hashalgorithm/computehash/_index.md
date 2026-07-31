---
title: ComputeHash()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat hash buffer.
type: docs
weight: 14
url: /id/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) metode

Membuat hash buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer sumber. |

### Nilai Kembalian

Nilai hash yang dihitung.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) metode

Membuat hash potongan buffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer sumber. |
| offset | int | Offset dalam buffer sumber. |
| count | int | Jumlah byte yang digunakan dari buffer sumber. |

### Nilai Kembalian

Nilai hash yang dihitung.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) metode

Membaca aliran sampai akhir dan menghitung hash untuk data yang dibaca.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Aliran untuk membaca data. |

### Nilai Kembalian

Nilai hash yang dihitung untuk seluruh data aliran.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashAlgorithm](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)