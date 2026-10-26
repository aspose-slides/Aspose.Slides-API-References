---
title: ConstCast()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: نهاية عمليات التحويل غير المفضلة.
type: docs
weight: 2575
url: /ar/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) دالة

نهاية عمليات التحويل غير المفضلة.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع العنصر الهدف. |
| TFrom | نوع العنصر المصدر. |

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا سُمح بالتحويل أو nullptr وإلا.

## ملاحظات

ينفّذ تحويل const على كائنات [SmartPtr](../smartptr/).

## انظر أيضًا

* الفئة [SmartPtr](../smartptr/)
* هيكل [CastResult](../castresult/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)