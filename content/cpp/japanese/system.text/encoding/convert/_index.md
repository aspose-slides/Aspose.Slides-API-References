---
title: Convert()
second_title: Aspose.Slides for C++ API リファレンス
description: 2つのエンコーディング間でバイトを変換します。
type: docs
weight: 378
url: /ja/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) メソッド

バイトを2つのエンコーディング間で変換します。

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 元のエンコーディング。 |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 目的のエンコーディング。 |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 変換するバイト。 |

### 戻り値

変換されたバイト。

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) メソッド

バイトを2つのエンコーディング間で変換します。

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 元のエンコーディング。 |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 目的のエンコーディング。 |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 変換するバイト。 |
| index | int | スライスの開始位置。 |
| count | int | スライスのサイズ。 |

### 戻り値

変換されたバイト。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)