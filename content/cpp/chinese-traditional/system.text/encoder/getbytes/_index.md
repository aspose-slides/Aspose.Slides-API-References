---
title: GetBytes()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得編碼�緩衝區產生的位元組。
type: docs
weight: 53
url: /zh-hant/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) 方法

取得編碼緩衝區產生的位元組。

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |
| charIndex | int | 來源陣列的偏移。 |
| charCount | int | 來源子陣列的長度。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 目標位元組緩衝區。 |
| byteIndex | int | 目標緩衝區的偏移。 |
| flush | **bool** | 如果為 true，則在計算後清除內部編碼器狀態。 |

### 返回值

寫入的位元組數。

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) 方法

取得編碼緩衝區產生的位元組。

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chars | const char_t * | 要編碼的字元。 |
| charCount | int | 來源陣列的長度。 |
| bytes | **uint8_t** * | 目標位元組緩衝區。 |
| byteCount | int | 目標緩衝區的大小。 |
| flush | **bool** | 如果為 true，則在計算後清除內部編碼器狀態。 |

### 返回值

寫入的位元組數。

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Encoder](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)