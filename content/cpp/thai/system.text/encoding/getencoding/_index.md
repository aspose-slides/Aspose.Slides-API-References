---
title: GetEncoding()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ดึงการเข้ารหัสตามชื่อ.
type: docs
weight: 508
url: /th/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) method

ดึงการเข้ารหัสตามชื่อ.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |

### ค่าที่คืน

[Encoding](../) of specified name.

## Encoding::GetEncoding(int) method

ดึงการเข้รหัสตาม codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Codepage number. |

### ค่าที่คืน

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) method

ดึงการเข้รหัสตาม codepage.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | Codepage number. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### ค่าที่คืน

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) method

ดึงการเข้รหัสตามชื่อ.

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) name. |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | Fallback to use for encoding. |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | Fallback to use for decoding. |

### ค่าที่คืน

[Encoding](../) of specified name.

## ดูเพิ่มเติม

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* คลาส [String](../../../system/string/)
* คลาส [Encoding](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)