---
title: DynamicCast()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينفذ تحويلًا ديناميكيًا على كائنات Exception.
type: docs
weight: 2536
url: /ar/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) دالة

ينفذ تحويل ديناميكي على كائنات Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TTo | نوع Exception الهدف. |
| TFrom | نوع Exception المصدر. |

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| obj | const TFrom\& | مؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

مهمل
:   متروك للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) دالة

ينفذ تحويل ديناميكي على كائنات [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TTo | نوع العنصر المستهدف. |
| TFrom | نوع العنصر المصدر. |

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | مؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

مهمل
:   متروك للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## System::DynamicCast(SmartPtr\<TFrom\>) دالة

يفك تغليف enum المعبأ عبر التحويل.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TTo | نوع enum الهدف. |
| TFrom | نوع العنصر المصدر. |

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | مؤشر إلى الكائن الذي يُفك منه البيانات. |

### قيمة الإرجاع

قيمة enum غير مغلفة.

مهمل
:   متروك للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## System::DynamicCast(std::nullptr_t) دالة

ينفذ تحويل ديناميكي لكائنات null.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TTo | نوع العنصر المستهدف. |

### قيمة الإرجاع

nullptr.

مهمل
:   متروك للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## System::DynamicCast(TFrom\&) دالة

ينفذ تحويل ديناميكي على كائنات غير مؤشرات.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TTo | النوع المستهدف. |
| TFrom | النوع المصدر. |

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| obj | TFrom\& | كائن المصدر. |

### قيمة الإرجاع

نتيجة التحويل.

مهمل
:   متروك للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## System::DynamicCast(SmartPtr\<TFrom\>) دالة

ينفذ تحويل ديناميكي على كائنات Objects إلى كائنات Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TTo | نوع Exception الهدف. |
| TFrom | نوع [Object](../object/). |

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | مؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

مهمل
:   متروك للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## System::DynamicCast(TFrom) دالة

ينفذ تحويل ديناميكي من IntPtr إلى مؤشر.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### معلمات القالب

| معامل | وصف |
| --- | --- |
| TTo | النوع المستهدف. |
| TFrom | النوع المصدر. |

### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| value | TFrom | قيمة IntPtr المصدر. |

### قيمة الإرجاع

نتيجة التحويل.

مهمل
:   متروك للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## انظر أيضاً

* فئة [SmartPtr](../smartptr/)
* فئة [Object](../object/)
* بنية [IsExceptionWrapper](../isexceptionwrapper/)
* بنية [CastResult](../castresult/)
* بنية [IsSmartPtr](../issmartptr/)
* مساحة أسماء [System](../)
* مكتبة [Aspose.Slides](../../)