---
title: Is()
second_title: مرجع API Aspose.Slides برای C++
description: پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع جعبه‌شدنی (مقدار) که دقیقاً همانند آن‌ها هستند.
type: docs
weight: 92
url: /fa/system/objectext/is/
---
## ObjectExt::Is(const T\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع جعبه‌شدنی (value) که دقیقاً همانند آن‌ها هستند.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) برای تست عملگر 'is'. نادیده گرفته می‌شود. |

### مقدار بازگشت

همیشه صحیح

## ObjectExt::Is(const U\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع اشاره‌گر بهینه‌سازی‌شده برای کلاس‌های 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |
| U | نوع آزمایش‌شده. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const U\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع اشاره‌گر.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |
| U | نوع آزمایش‌شده. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const Object\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع مقدار.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const Object\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع غیرقابل‌تبدیل.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

همیشه غلط چون انواع غیرقابل‌تبدیل هستند.

## ObjectExt::Is(const SmartPtr\<U\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع اشاره‌گر.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع بسته‌ساز استثنا.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const SmartPtr\<Object\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع قابل‌null.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const SmartPtr\<Object\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع جعبه‌شدنی که عملگر == تعریف شده است.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const SmartPtr\<Object\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع جعبه‌شدنی بدون تعریف ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const SmartPtr\<V\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع مقدار بسته‌شده به اینترفیس‌ها.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |
| V | نوع شیء اشاره‌شده. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const SmartPtr\<U\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع شمارشی.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |
| U | نوع شیء اشاره‌شده. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const WeakPtr\<U\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای انواع شمارشی در مقابل اشاره‌گرهای ضعیف.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |
| U | نوع شیء اشاره‌شده. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) برای تست عملگر 'is'. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const Nullable\<U\>\&) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای نوع [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) نوع. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(const char16_t *) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای literals رشته‌ای.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## ObjectExt::Is(int32_t) متد

پیاده‌سازی ترجمه عملگر 'is'. تخصص برای literals عددی.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### پارامترهای قالب

| Parameter | Description |
| --- | --- |
| T | نوع هدف. |

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int32_t** | عدد صحیح. |

### مقدار بازگشت

درست اگر 'is' درست بازگرداند، در غیر این صورت غلط.

## مراجعه

* کلاس [ObjectExt](../)
* کلاس [Object](../../object/)
* کلاس [SmartPtr](../../smartptr/)
* کلاس [ExceptionWrapper](../../exceptionwrapper/)
* کلاس [WeakPtr](../../weakptr/)
* کلاس [Nullable](../../nullable/)
* ساختار [IsBoxable](../../isboxable/)
* ساختار [IsSmartPtr](../../issmartptr/)
* ساختار [IsExceptionWrapper](../../isexceptionwrapper/)
* ساختار [IsNullable](../../isnullable/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)