---
title: Exists()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان كائن Array المحدد يحتوي على عنصر يفي بمتطلبات الشرط المحدد.
type: docs
weight: 781
url: /ar/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) طريقة

يحدد ما إذا كان الكائن [Array](../) المحدد يحتوي على عنصر يفي بمتطلبات الشرط المحدد.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | المصفوفة للبحث عن العنصر فيها |
| match | std::function\<**bool**(T)> | كائن الدالة الذي يحدد المتطلبات ويتحقق مما إذا كان العنصر يفي بها |

### قيمة الإرجاع

صحيح إذا كانت **arr** تحتوي على عنصر يفي بالمتطلبات المحددة بواسطة **match**

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../arrayptr/)
* فئة [Array](../)
* نطاق الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)