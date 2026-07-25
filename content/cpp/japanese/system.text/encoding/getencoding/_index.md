---
title: GetEncoding()
second_title: Aspose.Slides for C++ API リファレンス
description: 名前でエンコーディングを取得します。
type: docs
weight: 508
url: /ja/system.text/encoding/getencoding/
---
## Encoding::GetEncoding(const String\&) メソッド

名前でエンコーディングを取得します。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) 名前。 |

### 戻り値

[Encoding](../) の指定された名前。

## Encoding::GetEncoding(int) メソッド

コードページでエンコーディングを取得します。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| codepage | int | コードページ番号。 |

### 戻り値

[Encoding](../) の指定されたコードページ。

## Encoding::GetEncoding(int, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) メソッド

コードページでエンコーディングを取得します。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(int codepage, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| codepage | int | コードページ番号。 |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | エンコーディングに使用するフォールバック。 |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | デコードに使用するフォールバック。 |

### 戻り値

[Encoding](../) の指定されたコードページ。

## Encoding::GetEncoding(const String\&, const EncoderFallbackPtr\&, const DecoderFallbackPtr\&) メソッド

名前でエンコーディングを取得します。

```cpp
static EncodingPtr System::Text::Encoding::GetEncoding(const String &name, const EncoderFallbackPtr &encoder_fallback, const DecoderFallbackPtr &decoder_fallback)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | [Encoding](../) 名前。 |
| encoder_fallback | const [EncoderFallbackPtr](../../../system/encoderfallbackptr/)\& | エンコーディングに使用するフォールバック。 |
| decoder_fallback | const [DecoderFallbackPtr](../../../system/decoderfallbackptr/)\& | デコードに使用するフォールバック。 |

### 戻り値

[Encoding](../) の指定された名前。

## 参照

* 型定義 [EncodingPtr](../../../system/encodingptr/)
* 型定義 [EncoderFallbackPtr](../../../system/encoderfallbackptr/)
* 型定義 [DecoderFallbackPtr](../../../system/decoderfallbackptr/)
* クラス [String](../../../system/string/)
* クラス [Encoding](../)
* 名前空間 [System::Text](../../)
* ライブラリ [Aspose.Slides](../../../)