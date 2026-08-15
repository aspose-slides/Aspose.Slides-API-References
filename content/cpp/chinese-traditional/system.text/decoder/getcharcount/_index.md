---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 參考
description: 取得解碼緩衝區所需的字元數。
type: docs
weight: 40
url: /zh-hant/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) method

取得解碼緩衝區所需的字元數。

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| index | int | [Buffer](../../../system/buffer/) 偏移量。 |
| count | int | 要解碼的位元組數。 |

### 回傳值

解碼緩衝區所需的字元數。

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) method

取得解碼緩衝區所需的字元數。

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| index | int | [Buffer](../../../system/buffer/) 偏移量。 |
| count | int | 要解碼的位元組數。 |
| flush | **bool** | 如果為 true，則在計算後清除內部解碼器狀態。 |

### 回傳值

解碼緩衝區所需的字元數。

## Decoder::GetCharCount(const uint8_t *, int, bool) method

取得解碼緩衝區所需的字元數。

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| count | int | 要解碼的位元組數。 |
| flush | **bool** | 如果為 true，則在計算後清除內部解碼器狀態。 |

### 回傳值

解碼緩衝區所需的字元數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [Decoder](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)