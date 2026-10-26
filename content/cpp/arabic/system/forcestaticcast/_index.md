---
title: ForceStaticCast()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بإجراء تحويل ثابت حقيقي على كائنات SmartPtr.
type: docs
weight: 2588
url: /ar/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) دالة

يقوم بإجراء تحويل ثابت حقيقي على كائنات [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع العنصر المستهدف. |
| TFrom | نوع العنصر المصدر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا به، وإلا فإن السلوك غير معرف.

## انظر أيضًا

* فئة [SmartPtr](../smartptr/)
* بنية [CastResult](../castresult/)
* نطاق [System](../)
* مكتبة [Aspose.Slides](../../)