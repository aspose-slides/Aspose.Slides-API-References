---
title: GetByteCount()
second_title: مرجع API Aspose.Slides برای C++
description: تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را برمی‌گرداند.
type: docs
weight: 235
url: /fa/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) method

تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را بر می‌گرداند.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | بافر کاراکترها. |
| index | int | آغاز برش. |
| count | int | اندازه برش. |

### مقدار بازگشت

اندازهٔ بافر مورد نیاز.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) method

تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را بر می‌گرداند.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | بافر کاراکترها. |
| index | int | آغاز برش. |
| count | int | اندازه برش. |

### مقدار بازگشت

اندازهٔ بافر مورد نیاز.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) method

تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را بر می‌گرداند.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | بافر کاراکترها. |
| index | int | آغاز برش. |
| count | int | اندازه برش. |

### مقدار بازگشت

اندازهٔ بافر مورد نیاز.

## Encoding::GetByteCount(const String\&) method

تعداد کاراکترهای مورد نیاز برای رمزگذاری یک رشته را بر می‌گرداند.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) برای رمزگذاری. |

### مقدار بازگشت

اندازهٔ بافر مورد نیاز.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) method

تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را بر می‌گرداند.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | بافر کاراکترها. |

### مقدار بازگشت

اندازهٔ بافر مورد نیاز.

## Encoding::GetByteCount(const char_t *, int) method

تعداد کاراکترهای مورد نیاز برای رمزگذاری یک بافر کاراکتر را بر می‌گرداند.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chars | const char_t * | بافر کاراکترها. |
| count | int | [Buffer](../../../system/buffer/) اندازه. |

### مقدار بازگشت

اندازهٔ بافر مورد نیاز.

## موارد مرتبط

* تعریف‌نام [ArrayPtr](../../../system/arrayptr/)
* کلاس [Encoding](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)