---
title: StaticCast_noexcept()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينفذ تحويل ثابت على كائنات SmartPtr.
type: docs
weight: 2549
url: /ar/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) دالة


ينفّذ تحويل ثابت على كائنات [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع العنصر الهدف. |
| TFrom | نوع العنصر المصدر. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا سُمح بالتحويل أو nullptr خلاف ذلك.

متقادمة
:   متروكة للحفاظ على التوافق مع الإصدارات السابقة. استخدم AsCast بدلاً من ذلك.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) دالة


ينفّذ تحويل ثابت على كائنات [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع العنصر الهدف. |
| TFrom | نوع العنصر المصدر. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا سُمح بالتحويل أو nullptr خلاف ذلك.

متقادمة
:   متروكة للحفاظ على التوافق مع الإصدارات السابقة. استخدم AsCast بدلاً من ذلك.

## System::StaticCast_noexcept(const TFrom\&) دالة


ينفّذ تحويل ثابت على كائنات Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع Exception الهدف. |
| TFrom | نوع Exception المصدر. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const TFrom\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا سُمح بالتحويل أو nullptr خلاف ذلك.

متقادمة
:   متروكة للحفاظ على التوافق مع الإصدارات السابقة. استخدم AsCast بدلاً من ذلك.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) دالة


ينفّذ تحويل ثابت على كائنات إلى كائنات Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع Exception الهدف. |
| TFrom | [Object](../object/) نوع. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا سُمح بالتحويل أو nullptr خلاف ذلك.

متقادمة
:   متروكة للحفاظ على التوافق مع الإصدارات السابقة. استخدم AsCast بدلاً من ذلك.

## انظر أيضًا

* الفئة [SmartPtr](../smartptr/)
* الفئة [WeakPtr](../weakptr/)
* الفئة [Object](../object/)
* البنية [IsExceptionWrapper](../isexceptionwrapper/)
* البنية [CastResult](../castresult/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)