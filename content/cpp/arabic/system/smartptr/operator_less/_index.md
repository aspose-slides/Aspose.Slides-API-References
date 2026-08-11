---
title: operator<()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفر سلوك مقارنة أصغر لفئة SmartPtr.
type: docs
weight: 235
url: /ar/system/smartptr/operator_less/
---
## SmartPtr::operator<(Y *) const طريقة

يوفر سلوك مقارنة أصغر للفئة [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(Y *p) const
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| Y | نوع المؤشر للمقارنة بالمرجع الحالي. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| p | Y * | المؤشر للمقارنة بالمرجع الحالي. |

### قيمة الإرجاع

صحيح إذا كان الكائن المشار إليه بواسطة [SmartPtr](../) هو 'أقل' من p وإلا خاطئ.

## SmartPtr::operator<(SmartPtr\<Y\> const\&) const طريقة

يوفر سلوك مقارنة أصغر للفئة [SmartPtr](../).

```cpp
template<class Y> bool System::SmartPtr<T>::operator<(SmartPtr<Y> const &x) const
```

### معاملات القالب

| المعامل | الوصف |
| --- | --- |
| Y | نوع المؤشر للمقارنة بالمرجع الحالي. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | [SmartPtr](../)\<Y\> const\& | المؤشر للمقارنة بالمرجع الحالي. |

### قيمة الإرجاع

صحيح إذا كان الكائن المشار إليه بواسطة [SmartPtr](../) هو 'أقل' من x وإلا خاطئ.

## انظر أيضًا

* فئة [SmartPtr](../)
* نطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)