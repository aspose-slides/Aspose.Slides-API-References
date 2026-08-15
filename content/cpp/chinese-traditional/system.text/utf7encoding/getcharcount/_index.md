---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 參考
description: 取得解碼位元組緩衝區所需的字元數。
type: docs
weight: 79
url: /zh-hant/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 方法

取得解碼位元組緩衝區所需的字元數。

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 待解碼的位元組。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 傳回值

字元的數量。

## UTF7Encoding::GetCharCount(const uint8_t *, int) 方法

取得解碼位元組緩衝區所需的字元數。

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | 待解碼的位元組。 |
| count | int | 位元組數量。 |

### 傳回值

字元的數量。

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 方法

取得解碼位元組緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 待解碼的位元組。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 傳回值

字元的數量。

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) 方法

取得解碼位元組緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 待解碼的位元組。 |

### 傳回值

字元的數量。

## UTF7Encoding::GetCharCount(const uint8_t *, int) 方法

取得解碼位元組緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | 待解碼的位元組。 |
| count | int | 位元組數量。 |

### 傳回值

字元的數量。

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [UTF7Encoding](../)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)