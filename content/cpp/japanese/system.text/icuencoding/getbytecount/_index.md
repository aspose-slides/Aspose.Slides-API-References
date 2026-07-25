---
title: GetByteCount()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字バッファをエンコードするために必要な文字数を取得します。
type: docs
weight: 27
url: /ja/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) メソッド

文字バッファをエンコードするために必要な文字数を取得します。

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chars | const char_t * | 文字バッファ。 |
| count | int | [Buffer](../../../system/buffer/) サイズ。 |

### 戻り値

必要なバッファサイズ。

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) メソッド

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) メソッド

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) メソッド

RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) メソッド

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) メソッド

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) メソッド

RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)