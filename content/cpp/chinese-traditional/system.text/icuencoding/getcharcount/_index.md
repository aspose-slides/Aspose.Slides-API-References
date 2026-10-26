---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 參考
description: 取得解碼位元組緩衝區所需的字元數。
type: docs
weight: 53
url: /zh-hant/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) 方法

取得解碼位元組緩衝區所需的字元數。

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| count | int | 位元組計數。 |

### 返回值

字元數。

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 方法

取得解碼位元組緩衝區所需的字元數。

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

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) 方法

取得解碼位元組緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要解碼的位元組。 |

### 返回值

字元數。

## ICUEncoding::GetCharCount(const uint8_t *, int) 方法

取得解碼位元組緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 要解碼的位元組。 |
| count | int | 位元組計數。 |

### 返回值

字元數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)