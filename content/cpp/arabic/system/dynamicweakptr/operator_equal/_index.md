---
title: operator=()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينفّذ نقل الإسناد للمؤشر الذكي.
type: docs
weight: 27
url: /ar/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) طريقة

ينفّذ نقل الإسناد للمؤشر الذكي.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | المؤشر لنقل قيمة الإسناد منه. |

### قيمة الإرجاع

مرجع إلى الذات.

## DynamicWeakPtr::operator=(const SmartPtr_&) طريقة

ينفّذ إسناد النسخ للمؤشر الذكي.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | المؤشر لنسخ قيمة الإسناد منه. |

### قيمة الإرجاع

مرجع إلى الذات.

## DynamicWeakPtr::operator=(const SmartPtr<Q>&) طريقة

ينفّذ إسناد النسخ للمؤشر الذكي.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Q | نوع العنصر المشار إليه المصدر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | المؤشر لنسخ قيمة الإسناد منه. |

### قيمة الإرجاع

مرجع إلى الذات.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) طريقة

ينفّذ إسناد للمؤشر الذكي.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | قيمة المؤشر. |

### قيمة الإرجاع

مرجع إلى الذات.

## DynamicWeakPtr::operator=(std::nullptr_t) طريقة

يضبط المؤشر الذكي إلى null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### قيمة الإرجاع

مرجع إلى الذات.

## انظر أيضًا

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* فئة [DynamicWeakPtr](../)
* فئة [SmartPtr](../../smartptr/)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)