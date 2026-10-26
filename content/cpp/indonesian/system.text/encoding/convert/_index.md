---
title: Convert()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi byte di antara dua pengkodean.
type: docs
weight: 378
url: /id/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) method

Mengonversi byte di antara dua pengkodean.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Pengodean sumber. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Pengodean tujuan. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte yang akan dikonversi. |

### Nilai Kembali

Byte yang dikonversi.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) method

Mengonversi byte di antara dua pengkodean.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Pengodean sumber. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Pengodean tujuan. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte yang akan dikonversi. |
| index | int | Awal irisan. |
| count | int | Ukuran irisan. |

### Nilai Kembali

Byte yang dikonversi.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)