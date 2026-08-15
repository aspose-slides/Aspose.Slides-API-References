---
title: GetChars()
second_title: Aspose.Slides for C++ API 參考
description: 取得解碼緩衝區所產生的字元。
type: docs
weight: 53
url: /zh-hant/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 方法

取得解碼緩衝區所產生的字元。

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| byteIndex | int | 輸入緩衝區的偏移量。 |
| byteCount | int | 輸入緩衝區的大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目標字元緩衝區。 |
| charIndex | int | 目標陣列的偏移量。 |

### 回傳值

寫入的字元數。

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) 方法

取得解碼緩衝區所產生的字元。

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| byteIndex | int | 輸入緩衝區的偏移量。 |
| byteCount | int | 輸入緩衝區的大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目標字元緩衝區。 |
| charIndex | int | 目標陣列的偏移量。 |
| flush | **bool** | 若為 true，則在計算後清除內部解碼器狀態。 |

### 回傳值

寫入的字元數。

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) 方法

取得解碼緩衝區所產生的字元。

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| byteCount | int | 輸入緩衝區的大小。 |
| chars | char_t * | 目標字元緩衝區。 |
| charCount | int | 目標陣列的大小。 |
| flush | **bool** | 若為 true，則在計算後清除內部解碼器狀態。 |

### 回傳值

寫入的字元數。

## 另請參閱

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICUDecoder](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)