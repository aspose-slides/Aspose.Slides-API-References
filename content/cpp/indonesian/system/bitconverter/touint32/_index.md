---
title: ToUInt32()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengkonversi empat byte dari array yang ditentukan mulai dari indeks yang ditentukan menjadi nilai integer 32-bit tak bertanda.
type: docs
weight: 105
url: /id/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) metode

Mengkonversi empat byte dari array yang ditentukan mulai dari indeks yang ditentukan ke nilai integer 32-bit tak bertanda.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) yang berisi byte untuk dikonversi |
| startIndex | int | [Index](../../index/) dalam array tempat memulai pengambilan byte untuk konversi |

### Nilai Kembali

Nilai integer 32-bit tak bertanda yang dihasilkan dari konversi

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) metode

Mengkonversi empat byte dari array yang ditentukan mulai dari indeks yang ditentukan ke nilai integer 32-bit tak bertanda.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView yang berisi byte untuk dikonversi |
| startIndex | int | [Index](../../index/) dalam array tempat memulai pengambilan byte untuk konversi |

### Nilai Kembali

Nilai integer 32-bit tak bertanda yang dihasilkan dari konversi

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Class [BitConverter](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)