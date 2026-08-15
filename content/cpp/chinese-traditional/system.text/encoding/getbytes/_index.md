---
title: GetBytes()
second_title: Aspose.Slides for C++ API 參考
description: 取得對字元緩衝區編碼後產生的位元組。
type: docs
weight: 248
url: /zh-hant/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |
| char_index | int | 字元切片的起始位置。 |
| char_count | int | 要轉換的字元數。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區的偏移量。 |

### 返回值

寫入的位元組數。

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 要編碼的字元。 |
| char_index | int | 字元切片的起始位置。 |
| char_count | int | 要轉換的字元數。 |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區的偏移量。 |

### 返回值

寫入的位元組數。

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | 要編碼的字元。 |
| char_index | int | 字元切片的起始位置。 |
| char_count | int | 要轉換的字元數。 |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區的偏移量。 |

### 返回值

寫入的位元組數。

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 用於編碼。 |
| char_index | int | 字元切片的起始位置。 |
| char_count | int | 要轉換的字元數。 |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_index | int | 輸出緩衝區的偏移量。 |

### 返回值

寫入的位元組數。

## Encoding::GetBytes(const String\&) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 用於編碼。 |

### 返回值

[Buffer](../../../system/buffer/)，其中包含被編碼字元的表示。

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |
| index | int | 字元切片的起始位置。 |
| count | int | 要轉換的字元數。 |

### 返回值

[Buffer](../../../system/buffer/)，其中包含被編碼字元的表示。

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | 要編碼的字元。 |
| index | int | 字元切片的起始位置。 |
| count | int | 要轉換的字元數。 |

### 返回值

[Buffer](../../../system/buffer/)，其中包含被編碼字元的表示。

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 要編碼的字元。 |
| index | int | 字元切片的起始位置。 |
| count | int | 要轉換的字元數。 |

### 返回值

[Buffer](../../../system/buffer/)，其中包含被編碼字元的表示。

## Encoding::GetBytes(ArrayPtr\<char_t\>) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 要編碼的字元。 |

### 返回值

[Buffer](../../../system/buffer/)，其中包含被編碼字元的表示。

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) 方法

取得對字元緩衝區編碼後產生的位元組。

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 要編碼的字元。 |
| char_count | int | 要轉換的字元數。 |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 用於放置字元。 |
| byte_count | int | 輸出緩衝區的大小。 |

### 返回值

寫入的位元組數。

## 另請參閱

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Encoding](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)