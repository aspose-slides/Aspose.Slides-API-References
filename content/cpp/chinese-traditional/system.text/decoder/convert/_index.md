---
title: Convert()
second_title: Aspose.Slides for C++ API 參考文件
description: 將位元組轉換為字元。
type: docs
weight: 79
url: /zh-hant/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) 方法


將位元組轉換為字元。

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| byteIndex | int | 輸入緩衝區的偏移量。 |
| byteCount | int | 輸入緩衝區的大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目標字元緩衝區。 |
| charIndex | int | 目標陣列的偏移量。 |
| charCount | int | 目標陣列的大小。 |
| flush | **bool** | 如果為 true，則在計算後清除內部解碼器狀態。 |
| bytesUsed | int\& | 指向變數的參考，用於儲存已讀取的位元組計數。 |
| charsUsed | int\& | 指向變數的參考，用於儲存已寫入的字元計數。 |
| completed | **bool**\& | 指向變數的參考，如果輸入緩衝區已耗盡則設定為 true，否則設定為 false。 |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) 方法


將位元組轉換為字元。

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| byteCount | int | 輸入緩衝區的大小。 |
| chars | char_t * | 目標字元緩衝區。 |
| charCount | int | 目標陣列的大小。 |
| flush | **bool** | 如果為 true，則在計算後清除內部解碼器狀態。 |
| bytesUsed | int\& | 指向變數的參考，用於儲存已讀取的位元組計數。 |
| charsUsed | int\& | 指向變數的參考，用於儲存已寫入的字元計數。 |
| completed | **bool**\& | 指向變數的參考，如果輸入緩衝區已耗盡則設定為 true，否則設定為 false。 |

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [Decoder](../)
* 命名空間 [System::Text](../../)
* Library [Aspose.Slides](../../../)