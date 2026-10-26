---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得解碼位元緩衝所需的字元數。
type: docs
weight: 261
url: /zh-hant/system.text/encoding/getcharcount/
---
## Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 方法

取得解碼位元緩衝所需的字元數。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

字元數。

## Encoding::GetCharCount(ArrayPtr\<uint8_t\>) 方法

取得解碼位元緩衝所需的字元數。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |

### 返回值

字元數。

## Encoding::GetCharCount(const uint8_t *, int) 方法

取得解碼位元緩衝所需的字元數。

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| count | int | 位元組數量。 |

### 返回值

字元數。

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)