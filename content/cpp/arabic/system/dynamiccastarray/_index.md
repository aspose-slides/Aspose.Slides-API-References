---
title: DynamicCastArray()
second_title: Aspose.Slides لـ C++ مرجع API
description: يُجري تحويل عناصر المصفوفة المحددة إلى نوع مختلف.
type: docs
weight: 2991
url: /ar/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) دالة

يؤدي إلى تحويل عناصر المصفوفة المحددة إلى نوع مختلف.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| To | النوع الذي يُحوَّل إليه عناصر المصفوفة المحددة |
| From | نوع عناصر المصفوفة التي يُحوَّل منها |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | مؤشر مشترك إلى المصفوفة التي تحتوي على العناصر التي سيتم تحويلها |

### قيمة الإرجاع

مؤشر إلى مصفوفة جديدة تحتوي على عناصر من النوع **To** المكافئ لعناصر **from**

مهمل
:   تمّت الإضافة للتوافق مع الإصدارات السابقة. استخدم ExplicitCast بدلاً من ذلك.

## انظر أيضًا

* Typedef [SharedPtr](../sharedptr/)
* فئة [Array](../array/)
* مساحة الاسم [System](../)
* مكتبة [Aspose.Slides](../../)