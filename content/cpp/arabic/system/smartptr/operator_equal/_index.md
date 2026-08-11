---
title: operator=()
second_title: Aspose.Slides لـ C++ مرجع API
description: يقوم بنقل التخصيص لكائن SmartPtr. يصبح x غير قابل للاستخدام.
type: docs
weight: 27
url: /ar/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_\&&) طريقة

يقوم بنقل التخصيص لكائن [SmartPtr](../). يصبح x غير قابل للاستخدام.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | مؤشر إلى نقل التخصيص. |

### قيمة الإرجاع

مرجع إلى هذا الكائن.

## SmartPtr::operator=(const SmartPtr_\&) طريقة

يقوم بنسخ التخصيص لكائن [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | مؤشر إلى نسخ التخصيص. |

### قيمة الإرجاع

مرجع إلى هذا الكائن.

## SmartPtr::operator=(const SmartPtr\<Q\>\&) طريقة

يقوم بنسخ التخصيص لكائن [SmartPtr](../). يقوم بالتحويلات المطلوبة للنوع.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| Q | نوع الكائن الذي يشير إليه x. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | مؤشر إلى نسخ التخصيص. |

### قيمة الإرجاع

مرجع إلى هذا الكائن.

## SmartPtr::operator=(Pointee_ *) طريقة

يعيّن مؤشرًا غير معالج إلى كائن [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | قيمة المؤشر للتعيين. |

### قيمة الإرجاع

مرجع إلى هذا الكائن.

## SmartPtr::operator=(std::nullptr_t) طريقة

يضبط قيمة المؤشر إلى nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### قيمة الإرجاع

مرجع إلى هذا الكائن.

## انظر أيضًا

* تعريف نوع [SmartPtr_](../smartptr_/)
* تعريف نوع [Pointee_](../pointee_/)
* فئة [SmartPtr](../)
* نطاق الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)