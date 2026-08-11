---
title: Append()
second_title: مرجع API Aspose.Slides برای C++
description: کاراکتری را به سازنده اضافه می‌کند.
type: docs
weight: 118
url: /fa/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) متد

کاراکتر را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| c | char_t | مقدار کاراکتر. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(char_t, int) متد

کاراکترها را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| c | char_t | مقدار کاراکتر. |
| count | int | تعداد دفعاتی که کاراکتر درج‌شده باید تکرار شود. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) متد

آرایه‌ای از کاراکترها را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | کاراکترهای اضافه‌شده. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) متد

برش آرایه‌ای از کاراکترها را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | کاراکترهای اضافه‌شده. |
| startIndex | int | اندیس شروع برش. |
| charCount | int | طول برش. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(const String\&) متد

رشته را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) برای افزودن. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(const String\&, int, int) متد

برش رشته را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) برای افزودن. |
| startIndex | int | اندیس شروع برش. |
| charCount | int | طول برش. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(const SharedPtr\<T\>\&) متد

نمایش رشته‌ای شیء را به سازنده اضافه می‌کند.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### پارامترهای قالب

| پارامتر | شرح |
| --- | --- |
| T | [Object](../../../system/object/) نوع. |

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) برای سریال‌سازی و افزودن. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) متد

محتوای سازنده را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | سازنده‌ای که محتوا از آن اضافه می‌شود. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(float) متد

مقدار نقطه شناور را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| f | **float** | مقدار برای سریال‌سازی و افزودن. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(double) متد

مقدار نقطه شناور را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| df | **double** | مقدار برای سریال‌سازی و افزودن. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(int) متد

مقدار عدد صحیح را به سازنده اضافه می‌کند.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| i | int | مقدار برای سریال‌سازی و افزودن. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(T) متد

مقدار عددی را به سازنده اضافه می‌کند.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### پارامترهای قالب

| پارامتر | شرح |
| --- | --- |
| T | نوع عددی. |

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | T | مقدار برای سریال‌سازی و افزودن. |

### مقدار بازگشت

این اشاره‌گر.

## StringBuilder::Append(E) متد

نمایش رشته‌ای مقدار enum را به سازنده اضافه می‌کند.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### پارامترهای قالب

| پارامتر | شرح |
| --- | --- |
| E | [Enum](../../../system/enum/) نوع. |

### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| e | E | مقدار برای سریال‌سازی و افزودن. |

### مقدار بازگشت

این اشاره‌گر.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)