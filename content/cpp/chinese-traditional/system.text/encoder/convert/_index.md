---
title: Convert()
second_title: Aspose.Slides for C++ API 參考
description: 將字元轉換為位元組。
type: docs
weight: 79
url: /zh-hant/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) 方法


將字元轉換為位元組。

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |
| charIndex | int | 輸入緩衝區的偏移量。 |
| charCount | int | 輸入緩衝區的大小。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 目標位元組緩衝區。 |
| byteIndex | int | 目標陣列的偏移量。 |
| byteCount | int | 目標陣列的大小。 |
| flush | **bool** | 如果為 true，則在計算後清除內部編碼器狀態。 |
| charsUsed | int\& | 指向變數的參考，用於儲存已讀取的字元數。 |
| bytesUsed | int\& | 指向變數的參考，用於儲存已寫入的位元組數。 |
| completed | **bool**\& | 指向變數的參考，若輸入緩衝區已耗盡則設為 true，否則設為 false。 |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) 方法


將字元轉換為位元組。

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 要編碼的字元。 |
| charCount | int | 輸入緩衝區的大小。 |
| bytes | **uint8_t** * | 目標位元組緩衝區。 |
| byteCount | int | 目標陣列的大小。 |
| flush | **bool** | 如果為 true，則在計算後清除內部編碼器狀態。 |
| charsUsed | int\& | 指向變數的參考，用於儲存已讀取的字元數。 |
| bytesUsed | int\& | 指向變數的參考，用於儲存已寫入的位元組數。 |
| completed | **bool**\& | 指向變數的參考，若輸入緩衝區已耗盡則設為 true，否則設為 false。 |

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Encoder](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)