---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得解碼緩衝區所需的字元數。
type: docs
weight: 40
url: /zh-hant/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 方法

取得解碼緩衝區所需的字元數。

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| index | int | [Buffer](../../../system/buffer/) 位移。 |
| count | int | 要解碼的位元組數。 |

### 傳回值

解碼緩衝區所需的字元數。

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) 方法

取得解碼緩衝區所需的字元數。

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| index | int | [Buffer](../../../system/buffer/) 位移。 |
| count | int | 要解碼的位元組數。 |
| flush | **bool** | 如果為 true，則在計算後清除內部解碼器狀態。 |

### 傳回值

解碼緩衝區所需的字元數。

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) 方法

取得解碼緩衝區所需的字元數。

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| count | int | 要解碼的位元組數。 |
| flush | **bool** | 如果為 true，則在計算後清除內部解碼器狀態。 |

### 傳回值

解碼緩衝區所需的字元數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICUDecoder](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)