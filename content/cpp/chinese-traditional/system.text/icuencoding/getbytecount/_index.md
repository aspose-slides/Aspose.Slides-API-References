---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 參考
description: 取得編碼字元緩衝區所需的字元數。
type: docs
weight: 27
url: /zh-hant/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) 方法

取得編碼字元緩衝區所需的字元數。

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| chars | const char_t * | 字元緩衝區。 |
| count | int | [Buffer](../../../system/buffer/) 大小。 |

### 返回值

所需緩衝區大小。

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) 方法

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) 方法

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## 另請參閱

* 類型別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [ICUEncoding](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Text](../../)
* 程式庫 [Aspose.Slides](../../../)