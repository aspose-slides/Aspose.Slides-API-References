---
title: GetBytes()
second_title: Aspose.Slides for C++ API 參考
description: 取得編碼字元緩衝區所產生的位元組。
type: docs
weight: 66
url: /zh-hant/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |
| char_index | int | 字元片段的起始位置。 |
| char_count | int | 要轉換的字元數量。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區偏移量。 |

### 回傳值

寫入的位元組數。

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | const char_t * | 要編碼的字元。 |
| char_count | int | 要轉換的字元數量。 |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_count | int | 輸出緩衝區大小。 |

### 回傳值

寫入的位元組數。

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 用於編碼。 |
| char_index | int | 字元片段的起始位置。 |
| char_count | int | 要轉換的字元數量。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區偏移量。 |

### 回傳值

寫入的位元組數。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |
| char_index | int | 字元片段的起始位置。 |
| char_count | int | 要轉換的字元數量。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區偏移量。 |

### 回傳值

寫入的位元組數。

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 要編碼的字元。 |
| char_index | int | 字元片段的起始位置。 |
| char_count | int | 要轉換的字元數量。 |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區偏移量。 |

### 回傳值

寫入的位元組數。

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | 要編碼的字元。 |
| char_index | int | 字元片段的起始位置。 |
| char_count | int | 要轉換的字元數量。 |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區偏移量。 |

### 回傳值

寫入的位元組數。

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 用於編碼。 |
| char_index | int | 字元片段的起始位置。 |
| char_count | int | 要轉換的字元數量。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區偏移量。 |

### 回傳值

寫入的位元組數。

## UTF7Encoding::GetBytes(const String\&) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 用於編碼。 |

### 回傳值

[Buffer](../../../system/buffer/) 保存已編碼字元的表示。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |
| index | int | 字元片段的起始位置。 |
| count | int | 要轉換的字元數量。 |

### 回傳值

[Buffer](../../../system/buffer/) 保存已編碼字元的表示。

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | 要編碼的字元。 |
| index | int | 字元片段的起始位置。 |
| count | int | 要轉換的字元數量。 |

### 回傳值

[Buffer](../../../system/buffer/) 保存已編碼字元的表示。

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 要編碼的字元。 |
| index | int | 字元片段的起始位置。 |
| count | int | 要轉換的字元數量。 |

### 回傳值

[Buffer](../../../system/buffer/) 保存已編碼字元的表示。

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |

### 回傳值

[Buffer](../../../system/buffer/) 保存已編碼字元的表示。

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) 方法

取得編碼字元緩衝區所產生的位元組。

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | const char_t * | 要編碼的字元。 |
| char_count | int | 要轉換的字元數量。 |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_count | int | 輸出緩衝區大小。 |

### 回傳值

寫入的位元組數。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)