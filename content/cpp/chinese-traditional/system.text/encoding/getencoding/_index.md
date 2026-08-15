---
title: GetEncoding()
second_title: Aspose.Slides for C++ API 參考文件
description: 依名稱取得編碼。
type: docs
weight: 508
url: /zh-hant/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) 方法

根據名稱取得編碼。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) 名稱。 |

### 返回值

[Encoding](../) of specified name.

## Encoding::GetEncoding(int) 方法

根據代碼頁取得編碼。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| codepage | int | 代碼頁號。 |

### 返回值

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) 方法

根據代碼頁取得編碼。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| codepage | int | 代碼頁號。 |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | 用於編碼的回退。 |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | 用於解碼的回退。 |

### 返回值

[Encoding](../) of specified codepage.

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) 方法

根據名稱取得編碼。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) 名稱。 |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | 用於編碼的回退。 |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | 用於解碼的回退。 |

### 返回值

[Encoding](../) of specified name.

## 參見

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)