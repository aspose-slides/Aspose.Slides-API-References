---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 參考
description: 取得編碼字元緩衝區所需的字元數。
type: docs
weight: 235
url: /zh-hant/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method

取得編碼字元緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 字元緩衝區。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需的緩衝區大小。

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method

取得編碼字元緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 字元緩衝區。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需的緩衝區大小。

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method

取得編碼字元緩衝區所需的字元數。

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 字元緩衝區。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需的緩衝區大小。

## Encoding::GetByteCount(const String\&) method

取得編碼字串所需的字元數。

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 要編碼的 [String](../../../system/string/)。 |

### 返回值

所需的緩衝區大小。

## Encoding::GetByteCount(ArrayPtr\<char_t\>) method

取得編碼字元緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 字元緩衝區。 |

### 返回值

所需的緩衝區大小。

## Encoding::GetByteCount(const char_t *, int) method

取得編碼字元緩衝區所需的字元數。

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| chars | const char_t * | 字元緩衝區。 |
| count | int | [Buffer](../../../system/buffer/) 大小。 |

### 返回值

所需的緩衝區大小。

## 另請參閱

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)