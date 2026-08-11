---
title: Unbox()
second_title: Aspose.Slides برای C++ مرجع API
description: مقادیر نوع مقدار را پس از تبدیل به Object باز می‌کند. پیاده‌سازی برای انواع enum.
type: docs
weight: 53
url: /fa/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) متد

مقادیر نوع مقدار را پس از تبدیل به [Object](../../object/) باز می‌کند. پیاده‌سازی برای انواع enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | [Enum](../../enum/) نوع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) برای باز کردن. |

## مقدار بازگشتی

[Enum](../../enum/) مقدار.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) متد

مقادیر نوع مقدار را پس از تبدیل به [Object](../../object/) باز می‌کند. پیاده‌سازی برای انواع غیر-enum و غیر-nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) برای باز کردن. |

## مقدار بازگشتی

مقدار بازشده.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) متد

مقادیر نوع مقدار را پس از تبدیل به [Object](../../object/) باز می‌کند. پیاده‌سازی برای انواع غیر-enum و غیر-nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) برای باز کردن. |

## مقدار بازگشتی

مقدار بازشده.

## ObjectExt::Unbox(E) متد

انواع enum را به عدد صحیح باز می‌کند.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع عدد صحیح مقصد. |
| E | نوع enum منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| e | E | مقدار برای باز کردن. |

## مقدار بازگشتی

نمایش عددی enum.

## ObjectExt::Unbox(E) متد

انواع enum را تبدیل می‌کند.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع enum مقصد. |
| E | نوع enum منبع. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| e | E | مقدار برای باز کردن. |

## مقدار بازگشتی

مقدار enum تبدیل‌شده.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) متد

مقادیر رشته‌ای را باز می‌کند.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) برای باز کردن |

## مقدار بازگشتی

[String](../../string/) نمایش رشته جعبه‌شده، می‌تواند null باشد اگر رشته جعبه‌شده null بود.

## همچنین ببینید

* کلاس [SmartPtr](../../smartptr/)
* کلاس [Object](../../object/)
* کلاس [ObjectExt](../)
* کلاس [String](../../string/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)