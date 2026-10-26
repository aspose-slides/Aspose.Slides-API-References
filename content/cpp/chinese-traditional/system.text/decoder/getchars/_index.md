---
title: GetChars()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得解碼緩衝區後產生的字元。
type: docs
weight: 53
url: /zh-hant/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 方法

取得解碼緩衝區後產生的字元。

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| byteIndex | int | 輸入緩衝區偏移。 |
| byteCount | int | 輸入緩衝區大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目標字元緩衝區。 |
| charIndex | int | 目標陣列偏移。 |

### 返回值

寫入的字元數。

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) 方法

取得解碼緩衝區後產生的字元。

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| byteIndex | int | 輸入緩衝區偏移。 |
| byteCount | int | 輸入緩衝區大小。 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 目標字元緩衝區。 |
| charIndex | int | 目標陣列偏移。 |
| flush | **bool** | 若為 true，則在計算後清除內部解碼器狀態。 |

### 返回值

寫入的字元數。

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) 方法

取得解碼緩衝區後產生的字元。

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| byteCount | int | 輸入緩衝區大小。 |
| chars | char_t * | 目標字元緩衝區。 |
| charCount | int | 目標陣列大小。 |
| flush | **bool** | 若為 true，則在計算後清除內部解碼器狀態。 |

### 返回值

寫入的字元數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 類別 [Decoder](../)
* 名稱空間 [System::Text](../../)
* Library [Aspose.Slides](../../../)