---
title: Insert()
second_title: مرجع API Aspose.Slides برای C++
description: یک رشته را در موقعیت ثابت سازنده وارد می‌کند.
type: docs
weight: 183
url: /fa/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) متد

یک رشته را در موقعیت ثابت سازنده وارد می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | موقعیتی که کاراکترها در آن وارد می‌شوند. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) برای وارد کردن. |

### مقدار برگشتی

این اشاره‌گر.

## StringBuilder::Insert(int32_t, const String\&, int32_t) متد

رشته‌ای تکراری را در موقعیت ثابت سازنده وارد می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | **int32_t** | موقعیتی که کاراکترها در آن وارد می‌شوند. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) برای وارد کردن. |
| count | **int32_t** | تعداد دفعاتی که رشته **value** تکرار می‌شود. |

### مقدار برگشتی

این اشاره‌گر.

## StringBuilder::Insert(int, char_t) متد

یک کاراکتر را در موقعیت ثابت سازنده وارد می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | موقعیتی که کاراکترها در آن وارد می‌شوند. |
| ch | char_t | کاراکتری که وارد می‌شود. |

### مقدار برگشتی

این اشاره‌گر.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) متد

کاراکترها را در موقعیت ثابت سازنده وارد می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | موقعیتی که کاراکترها در آن وارد می‌شوند. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) برای وارد کردن برش از. |
| startIndex | int | [Array](../../../system/array/) شاخص ابتدای برش. |
| charCount | int | [Array](../../../system/array/) طول برش. |

### مقدار برگشتی

این اشاره‌گر.

## StringBuilder::Insert(int, T) متد

مقداری را در موقعیت ثابت سازنده وارد می‌کند.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| Parameter | نوع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | موقعیتی که کاراکترها در آن وارد می‌شوند. |
| value | T | مقداری که قالب‌بندی و وارد می‌شود. |

### مقدار برگشتی

این اشاره‌گر.

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [StringBuilder](../)
* کلاس [String](../../../system/string/)
* فضای نام [System::Text](../../)
* کتابخانه [Aspose.Slides](../../../)