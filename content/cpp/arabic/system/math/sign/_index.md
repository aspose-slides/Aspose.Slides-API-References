---
title: Sign()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد إشارة القيمة الصحيحة الموقعة المحددة.
type: docs
weight: 274
url: /ar/system/math/sign/
---
## Math::Sign(T) طريقة

يحدد إشارة القيمة الصحيحة الموقعة المحددة.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | النوع الصحيح الموقّع |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | T | القيمة لتحديد إشارة لها |

### قيمة الإرجاع

- 1 إذا كان **value** أقل من 0؛ 0 إذا كان **value** يساوي 0؛ 1 إذا كان **value** أكبر من 0

## Math::Sign(T) طريقة

يحدد إشارة القيمة العائمة المحددة.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع النقطة العائمة للوسيط |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | T | القيمة لتحديد إشارة لها |

### قيمة الإرجاع

- 1 إذا كان **value** أقل من 0؛ 0 إذا كان **value** يساوي 0؛ 1 إذا كان **value** أكبر من 0

## Math::Sign(const Decimal\&) طريقة

يحدد إشارة القيمة العشرية المحددة.

```cpp
static int System::Math::Sign(const Decimal &value)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | القيمة لتحديد إشارة لها |

### قيمة الإرجاع

- 1 إذا كان **value** أقل من 0؛ 0 إذا كان **value** يساوي 0؛ 1 إذا كان **value** أكبر من 0

## انظر أيضا

* فئة [Decimal](../../decimal/)
* بنية [Math](../)
* نطاق اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)