---
title: Find()
second_title: مرجع API Aspose.Slides للغة C++
description: يبحث عن العنصر الأول في المصفوفة المحددة الذي يطابق شروط المتنبئ المحدد.
type: docs
weight: 651
url: /ar/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) طريقة

يبحث عن العنصر الأول في المصفوفة المحددة الذي يطابق شروط المتنبئ المحدد.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) للبحث عن عنصر في |
| match | [System::Predicate](../../predicate/)\<T\> | متنبئ يحدد الشروط التي يُطابق بها عناصر المصفوفة |

### قيمة الإرجاع

نسخة من العنصر الأول في المصفوفة الذي يطابق الشروط المعرفة بواسطة المتنبئ، وإلا القيمة الافتراضية من النوع T

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* تعريف نوع [Predicate](../../predicate/)
* فئة [Array](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)