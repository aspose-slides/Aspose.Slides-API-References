---
title: DynamicCast_noexcept()
second_title: مرجع API Aspose.Slides للغة C++
description: تحويلات قديمة غير صالحة. سيتم إزالتها في الإصدارات المستقبلية.
type: docs
weight: 2523
url: /ar/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) الدالة

تحويلات قديمة غير صالحة. سيتم إزالتها في الإصدارات المستقبلية.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| TTo | نوع Exception الهدف. |
| TFrom | نوع Exception المصدر. |

### الوسائط

| معلمة | النوع | الوصف |
| --- | --- | --- |
| obj | const TFrom\& | مؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا أو nullptr خلاف ذلك.

## ملاحظات

يؤدي تحويلًا ديناميكيًا على كائنات Exception. متقَدِّم
:   ترك للتماشي مع الإصدارات السابقة. استخدم AsCast بدلاً من ذلك.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) الدالة

يؤدي تحويلًا ديناميكيًا على [SmartPtr](../smartptr/) كائنات.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| TTo | نوع العنصر الهدف. |
| TFrom | نوع العنصر المصدر. |

### الوسائط

| معلمة | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | مؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا أو nullptr خلاف ذلك.

متقَدِّم
:   ترك للتماشي مع الإصدارات السابقة. استخدم AsCast بدلاً من ذلك.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) الدالة

يؤدي تحويلًا ديناميكيًا على كائنات إلى كائنات Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| TTo | نوع Exception الهدف. |
| TFrom | نوع [Object](../object/). |

### الوسائط

| معلمة | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | مؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا أو nullptr خلاف ذلك.

متقَدِّم
:   ترك للتماشي مع الإصدارات السابقة. استخدم AsCast بدلاً من ذلك.

## انظر أيضاً

* فئة [SmartPtr](../smartptr/)
* فئة [Object](../object/)
* هيكل [IsExceptionWrapper](../isexceptionwrapper/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)