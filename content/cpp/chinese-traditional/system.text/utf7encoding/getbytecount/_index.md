---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得編碼字元緩衝區所需的字元數量。
type: docs
weight: 157
url: /zh-hant/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) 方法

取得編碼字元緩衝區所需的字元數量。

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 字元緩衝區。 |
| count | int | [Buffer](../../../system/buffer/) 大小。 |

### 返回值

所需緩衝區大小。

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) 方法

取得編碼字元緩衝區所需的字元數量。

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 字元緩衝區。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需緩衝區大小。

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) 方法

取得編碼字元緩衝區所需的字元數量。

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 字元緩衝區。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需緩衝區大小。

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) 方法

取得編碼字元緩衝區所需的字元數量。

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 字元緩衝區。 |
| index | int | 切片起始位置。 |
| count | int | 切片大小。 |

### 返回值

所需緩衝區大小。

## UTF7Encoding::GetByteCount(const String\&) 方法

取得編碼字串所需的字元數量。

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 要編碼。 |

### 返回值

所需緩衝區大小。

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) 方法

取得編碼字元緩衝區所需的字元數量。

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 字元緩衝區。 |

### 返回值

所需緩衝區大小。

## UTF7Encoding::GetByteCount(const char_t *, int) 方法

取得編碼字元緩衝區所需的字元數量。

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 字元緩衝區。 |
| count | int | [Buffer](../../../system/buffer/) 大小。 |

### 返回值

所需緩衝區大小。

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [UTF7Encoding](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Text](../../)
* 函式庫 [Aspose.Slides](../../../)