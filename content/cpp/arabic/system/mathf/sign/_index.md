---
title: Sign()
second_title: مرجع Aspose.Slides API لـ C++
description: يحدد إشارة القيمة الصحيحة الموقّعة المحددة.
type: docs
weight: 274
url: /ar/system/mathf/sign/
---
## MathF::Sign(T) طريقة


يحدد إشارة القيمة الصحيحة الموقعة المحددة.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع صحيح موقّع |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| value | T | القيمة لتحديد الإشارة |

### قيمة الإرجاع

- 1 إذا كانت **value** أصغر من 0؛ 0 إذا كانت **value** مساوية لـ 0؛ 1 إذا كانت **value** أكبر من 0

## MathF::Sign(T) طريقة


يحدد إشارة القيمة العائمة المحددة.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### معلمات القالب

| معامل | الوصف |
| --- | --- |
| T | نوع القيمة العائمة للمعامل |

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| value | T | القيمة لتحديد الإشارة |

### قيمة الإرجاع

- 1 إذا كانت **value** أصغر من 0؛ 0 إذا كانت **value** مساوية لـ 0؛ 1 إذا كانت **value** أكبر من 0

## انظر أيضًا

* بنية [MathF](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)