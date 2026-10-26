---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得編碼緩衝區所需的位元組數。
type: docs
weight: 40
url: /zh-hant/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) 方法


取得編碼緩衝區所需的位元組數。

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |
| index | int | [Buffer](../../../system/buffer/) 偏移量。 |
| count | int | 要編碼的字元數。 |
| flush | **bool** | 如果為 true，則在計算後清除內部編碼器狀態。 |

### 回傳值

編碼緩衝區所需的位元組數。

## Encoder::GetByteCount(const char_t *, int, bool) 方法


取得編碼緩衝區所需的位元組數。

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| chars | const char_t * | 要編碼的字元。 |
| count | int | 要編碼的字元數。 |
| flush | **bool** | 如果為 true，則在計算後清除內部編碼器狀態。 |

### 回傳值

編碼緩衝區所需的位元組數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)