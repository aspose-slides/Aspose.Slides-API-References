---
title: operator+()
second_title: مرجع API برای Aspose.Slides برای C++
description: عملگر ترکیب رشته.
type: docs
weight: 274
url: /fa/system/string/operator_plus/
---
## String::operator+(const String\&) const متد

[String](../) عملگر ترکیب.

```cpp
String System::String::operator+(const String &str) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) برای افزودن به انتهای رشتهٔ جاری. |

### مقدار برگشت

رشتهٔ ترکیب‌شده.

## String::operator+(const T\&) const متد

[String](../) ترکیب با مقدار ثابت رشته یا اشاره‌گر رشتهٔ کاراکتری.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | یکی از فرم‌های مقدار ثابت رشته یا اشاره‌گر رشتهٔ کاراکتری. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arg | const T\& | مورد برای ترکیب با رشتهٔ کنونی. |

### مقدار برگشت

رشتهٔ ترکیب‌شده.

## String::operator+(char_t) const متد

کاراکتر را به انتهای رشته اضافه می‌کند.

```cpp
String System::String::operator+(char_t x) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | char_t | کاراکتری که باید اضافه شود. |

### مقدار برگشت

[String](../) نتیجهٔ ترکیب.

## String::operator+(int) const متد

نمایش رشته‌ای مقدار عدد صحیح را به انتهای رشته اضافه می‌کند.

```cpp
String System::String::operator+(int i) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | int | مقدار عدد صحیح برای تبدیل به رشته و افزودن. |

### مقدار برگشت

[String](../) نتیجهٔ ترکیب.

## String::operator+(uint32_t) const متد

نمایش رشته‌ای مقدار عدد صحیح بدون علامت را به انتهای رشته اضافه می‌کند.

```cpp
String System::String::operator+(uint32_t i) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| i | **uint32_t** | مقداری برای تبدیل به رشته و افزودن. |

### مقدار برگشت

[String](../) نتیجهٔ ترکیب.

## String::operator+(double) const متد

نمایش رشته‌ای مقدار عدد شناور را به انتهای رشته اضافه می‌کند.

```cpp
String System::String::operator+(double d) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| d | **double** | مقداری برای تبدیل به رشته و افزودن. |

### مقدار برگشت

[String](../) نتیجهٔ ترکیب.

## String::operator+(int64_t) const متد

نمایش رشته‌ای مقدار عدد صحیح را به انتهای رشته اضافه می‌کند.

```cpp
String System::String::operator+(int64_t v) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| v | **int64_t** | مقداری برای تبدیل به رشته و افزودن. |

### مقدار برگشت

[String](../) نتیجهٔ ترکیب.

## String::operator+(const T\&) const متد

نمایش رشته‌ای شیء از نوع ارجاعی را به انتهای رشته اضافه می‌کند.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع اشاره‌گر. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) برای تبدیل به رشته با استفاده از فراخوانی [ToString()](../tostring/) و افزودن به رشتهٔ جاری. |

### مقدار برگشت

[String](../) نتیجهٔ ترکیب.

## String::operator+(const T\&) const متد

نمایش رشته‌ای شیء از نوع مقدار را به انتهای رشته اضافه می‌کند.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقداری برای فراخوانی [ToString()](../tostring/). |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) برای تبدیل به رشته با استفاده از فراخوانی [ToString()](../tostring/) و افزودن به رشتهٔ جاری. |

### مقدار برگشت

[String](../) نتیجهٔ ترکیب.

## String::operator+(T) const متد

نمایش رشته‌ای مقدار بولی را به انتهای رشته اضافه می‌کند.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقداری برای ترکیب با رشته. باید bool باشد |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) مقدار برای تبدیل به رشته و افزودن. |

### مقدار برگشت

[String](../) نتیجهٔ ترکیب.

## موارد مرتبط

* کلاس [String](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)