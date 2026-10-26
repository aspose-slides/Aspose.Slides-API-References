---
title: Convert()
second_title: Aspose.Slides for C++ API 參考文件
description: 將位元組轉換為字元。
type: docs
weight: 1
url: /zh-hant/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) 方法


將位元組轉換為字元。

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| byteCount | int | 輸入緩衝區大小。 |
| chars | char_t * | 目標字元緩衝區。 |
| charCount | int | 目標陣列大小。 |
| flush | **bool** | 若為 true，則在計算後清除內部解碼器狀態。 |
| bytesUsed | int\& | 用於儲存已讀位元組數量的變數參考。 |
| charsUsed | int\& | 用於儲存已寫入字元數量的變數參考。 |
| completed | **bool**\& | 變數參考，若輸入緩衝區已耗盡則設為 true，否則設為 false。 |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) 方法


將位元組轉換為字元。

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| byteIndex | int | 輸入緩衝區偏移量。 |
| byteCount | int | 輸入緩衝區大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目標字元緩衝區。 |
| charIndex | int | 目標陣列偏移量。 |
| charCount | int | 目標陣列大小。 |
| flush | **bool** | 若為 true，則在計算後清除內部解碼器狀態。 |
| bytesUsed | int\& | 用於儲存已讀位元組數量的變數參考。 |
| charsUsed | int\& | 用於儲存已寫入字元數量的變數參考。 |
| completed | **bool**\& | 變數參考，若輸入緩衝區已耗盡則設為 true，否則設為 false。 |

## 參見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [EncodingDecoder](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)