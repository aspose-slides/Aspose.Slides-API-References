---
title: GetByteCount()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را برمی‌گرداند.
type: docs
weight: 27
url: /fa/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) متد


Get the number of characters needed to encode a character buffer.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | بافر کاراکترها. |
| count | int | [Buffer](../../../system/buffer/) اندازه. |

### مقدار بازگشت

اندازه بافر مورد نیاز.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) متد


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) متد


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) متد


RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) متد


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) متد


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) متد


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICUEncoding](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)