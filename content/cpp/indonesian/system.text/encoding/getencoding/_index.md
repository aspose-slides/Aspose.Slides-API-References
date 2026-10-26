---
title: GetEncoding()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan encoding berdasarkan nama.
type: docs
weight: 508
url: /id/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) metode

Mendapatkan encoding berdasarkan nama.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nama. |

### Nilai Kembali

[Encoding](../) dari nama yang ditentukan.

## Encoding::GetEncoding(int) metode

Mendapatkan encoding berdasarkan codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codepage | int | Nomor codepage. |

### Nilai Kembali

[Encoding](../) dari codepage yang ditentukan.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metode

Mendapatkan encoding berdasarkan codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| codepage | int | Nomor codepage. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback yang digunakan untuk encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback yang digunakan untuk decoding. |

### Nilai Kembali

[Encoding](../) dari codepage yang ditentukan.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) metode

Mendapatkan encoding berdasarkan nama.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) nama. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback yang digunakan untuk encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback yang digunakan untuk decoding. |

### Nilai Kembali

[Encoding](../) dari nama yang ditentukan.

## Lihat Juga

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Kelas [String](../../../system/string/)
* Kelas [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)