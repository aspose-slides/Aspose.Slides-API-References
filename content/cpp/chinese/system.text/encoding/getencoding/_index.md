---
title: GetEncoding()
second_title: Aspose.Slides for C++ API 参考
description: 通过名称获取编码。
type: docs
weight: 508
url: /zh/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String&) 方法

通过名称获取编码。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) 名称。 |

### 返回值

[Encoding](../) 指定名称的编码。

## Encoding::GetEncoding(int) 方法

通过代码页获取编码。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| codepage | int | 代码页编号。 |

### 返回值

[Encoding](../) 指定代码页的编码。

## Encoding::GetEncoding(int, const EncoderFallbackPtr&, const DecoderFallbackPtr&) 方法

通过代码页获取编码。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| codepage | int | 代码页编号。 |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | 用于编码的回退。 |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | 用于解码的回退。 |

### 返回值

[Encoding](../) 指定代码页的编码。

## Encoding::GetEncoding(const String&, const EncoderFallbackPtr&, const DecoderFallbackPtr&) 方法

通过名称获取编码。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) 名称。 |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | 用于编码的回退。 |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | 用于解码的回退。 |

### 返回值

[Encoding](../) 指定名称的编码。

## 参见

* Typedef [EncodingPtr](../../../system/encodingptr/)
* Typedef [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* Typedef [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* 类 [String](../../../system/string/)
* 类 [Encoding](../)
* 命名空间 [System::Text](../../)
* Library [Aspose.Slides](../../../)