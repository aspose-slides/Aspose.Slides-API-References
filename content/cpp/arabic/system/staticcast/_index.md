---
title: StaticCast()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: ينفّذ تحويلًا ثابتًا على كائنات SmartPtr.
type: docs
weight: 2562
url: /ar/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) دالة


ينفّذ تحويلًا ثابتًا على كائنات [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع العنصر المستهدف. |
| TFrom | نوع العنصر المصدر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

متقَدَّم
:   تركت للتوافق العكسي. استخدم ExplicitCast بدلاً من ذلك.

## System::StaticCast(WeakPtr\<TFrom\> const\&) دالة


ينفّذ تحويلًا ثابتًا على كائنات [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع العنصر المستهدف. |
| TFrom | نوع العنصر المصدر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

متقَدَّم
:   تركت للتوافق العكسي. استخدم ExplicitCast بدلاً من ذلك.

## System::StaticCast(std::nullptr_t) دالة


ينفّذ تحويلًا ثابتًا للكائنات ذات القيمة null.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع العنصر المستهدف. |

### قيمة الإرجاع

nullptr.

متقَدَّم
:   تركت للتوافق العكسي. استخدم ExplicitCast بدلاً من ذلك.

## System::StaticCast(TFrom) دالة


تخصص للأنواع العددية.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) دالة


معالجة التحويل من [String](../string/) إلى [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) دالة


تخصص للأنواع العددية.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) دالة


ينفّذ تحويلًا ثابتًا على كائنات غير المؤشر.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | النوع المستهدف. |
| TFrom | النوع المصدر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const TFrom\& | كائن المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

متقَدَّم
:   تركت للتوافق العكسي. استخدم ExplicitCast بدلاً من ذلك.

## System::StaticCast(const TFrom\&) دالة


ينفّذ تحويلًا ثابتًا على كائنات Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع الاستثناء الهدف. |
| TFrom | نوع الاستثناء المصدر. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const TFrom\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

متقَدَّم
:   تركت للتوافق العكسي. استخدم ExplicitCast بدلاً من ذلك.

## System::StaticCast(SmartPtr\<TFrom\>) دالة


ينفّذ تحويلًا ثابتًا على الكائنات إلى كائنات Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع الاستثناء الهدف. |
| TFrom | [Object](../object/) نوع. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

متقَدَّم
:   تركت للتوافق العكسي. استخدم ExplicitCast بدلاً من ذلك.

## انظر أيضًا

* الفئة [SmartPtr](../smartptr/)
* الفئة [WeakPtr](../weakptr/)
* الفئة [String](../string/)
* الفئة [Object](../object/)
* هيكل [IsExceptionWrapper](../isexceptionwrapper/)
* هيكل [CastResult](../castresult/)
* هيكل [IsSmartPtr](../issmartptr/)
* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)