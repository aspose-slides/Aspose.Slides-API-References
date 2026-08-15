---
title: Convert()
second_title: Aspose.Slides for C++ API 參考
description: 在兩種編碼之間轉換位元組。
type: docs
weight: 378
url: /zh-hant/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) 方法

在兩種編碼之間轉換位元組。

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 來源編碼。 |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 目的編碼。 |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要轉換的位元組。 |

### 回傳值

已轉換的位元組。

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) 方法

在兩種編碼之間轉換位元組。

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 來源編碼。 |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | 目的編碼。 |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 要轉換的位元組。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 回傳值

已轉換的位元組。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)