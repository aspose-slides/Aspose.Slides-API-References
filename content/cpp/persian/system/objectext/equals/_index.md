---
title: Equals()
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 14
url: /fa/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) method

جایگزینی برای فراخوانی‌های C# [Object.Equals](../../object/equals/) که برای هر نوعی در C++ کار می‌کند. بارگذاری برای انواع اشاره‌گر هوشمند.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اول. |
| T2 | نوع شیء دوم. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | شیء اول. |
| another | const T2\& | شیء دوم. |

### مقدار بازگشت

True اگر اشیاء برابر در نظر گرفته شوند، false در غیر این صورت.

## ObjectExt::Equals(T, const T2\&) method

جایگزینی برای فراخوانی‌های C# [Object.Equals](../../object/equals/) که برای هر نوعی در C++ کار می‌کند. بارگذاری برای انواع ساختاری.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اول. |
| T2 | نوع شیء دوم. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | T | شیء اول. |
| another | const T2\& | شیء دوم. |

### مقدار بازگشت

True اگر اشیاء برابر در نظر گرفته شوند، false در غیر این صورت.

## ObjectExt::Equals(const T\&, const T2\&) method

جایگزینی برای فراخوانی‌های C# [Object.Equals](../../object/equals/) که برای هر نوعی در C++ کار می‌کند. بارگذاری برای انواع اسکالر.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| T | نوع شیء اول. |
| T2 | نوع شیء دوم. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const T\& | شیء اول. |
| another | const T2\& | شیء دوم. |

### مقدار بازگشت

True اگر اشیاء برابر در نظر گرفته شوند، false در غیر این صورت.

## ObjectExt::Equals(const char_t(&), String) method

جایگزینی برای فراخوانی‌های C# [Object.Equals](../../object/equals/) که برای هر نوعی در C++ کار می‌کند. بارگذاری برای مقایسه رشته‌ای با رشته ثابت.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| N | [String](../../string/) اندازه ثابت. |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) ثابت. |
| another | [String](../../string/) | [String](../../string/). |

### مقدار بازگشت

True اگر رشته‌ها مطابقت داشته باشند، false در غیر این صورت.

## ObjectExt::Equals(const float\&, const float\&) method

شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const **float**\& | مقدار نقطه شناور سمت چپ. |
| another | const **float**\& | مقدار نقطه شناور سمت راست. |

### مقدار بازگشت

True اگر **obj** و **another** هر دو NaN باشند یا برابر، false در غیر این صورت.

## ObjectExt::Equals(const double\&, const double\&) method

شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | const **double**\& | مقدار نقطه شناور سمت چپ. |
| another | const **double**\& | مقدار نقطه شناور سمت راست. |

### مقدار بازگشت

True اگر **obj** و **another** هر دو NaN باشند یا برابر، false در غیر این صورت.

## مراجع

* کلاس [ObjectExt](../)
* کلاس [String](../../string/)
* ساختار [IsExceptionWrapper](../../isexceptionwrapper/)
* ساختار [IsSmartPtr](../../issmartptr/)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)