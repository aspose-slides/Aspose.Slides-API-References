---
title: GetString()
second_title: Aspose.Slides for C++ API 參考
description: 將位元組緩衝區解碼為字串。
type: docs
weight: 313
url: /zh-hant/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) 方法

將位元組緩衝區解碼為字串。

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 用於讀取位元組。 |
| byte_count | int | 輸入緩衝區大小。 |

### 回傳值

[String](../../../system/string/) 個已解碼字元。

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) 方法

將位元組緩衝區解碼為字串。

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 用於讀取位元組。 |

### 回傳值

[String](../../../system/string/) 個已解碼字元。

## Encoding::GetString(ArrayPtr\<uint8_t\>) 方法

將位元組緩衝區解碼為字串。

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取位元組。 |

### 回傳值

[String](../../../system/string/) 個已解碼字元。

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) 方法

將位元組緩衝區解碼為字串。

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 用於讀取位元組。 |

### 回傳值

[String](../../../system/string/) 個已解碼字元。

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) 方法

將位元組緩衝區解碼為字串。

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) 用於讀取位元組。 |

### 回傳值

[String](../../../system/string/) 個已解碼字元。

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) 方法

將位元組緩衝區解碼為字串。

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於讀取位元組。 |
| index | int | 輸入緩衝區偏移量。 |
| count | int | 輸入緩衝區大小。 |

### 回傳值

[String](../../../system/string/) 個已解碼字元。

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) 方法

將位元組緩衝區解碼為字串。

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 用於讀取位元組。 |
| index | int | 輸入緩衝區偏移量。 |
| count | int | 輸入緩衝區大小。 |

### 回傳值

[String](../../../system/string/) 個已解碼字元。

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) 方法

將位元組緩衝區解碼為字串。

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) 用於讀取位元組。 |
| index | int | 輸入緩衝區偏移量。 |
| count | int | 輸入緩衝區大小。 |

### 回傳值

[String](../../../system/string/) 個已解碼字元。

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)