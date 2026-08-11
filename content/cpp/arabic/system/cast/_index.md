---
title: Cast()
second_title: مرجع Aspose.Slides للغة C++ API
description: يُجري التحويل على كائنات SmartPtr.
type: docs
weight: 2510
url: /ar/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) دالة

يُجري التحويل على كائنات [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### معلمات القالب

| المُعامل | الوصف |
| --- | --- |
| TTo | نوع العنصر المستهدف. |
| TFrom | نوع العنصر المصدر. |

### الوسائط

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | المؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا.

## انظر أيضًا

* الفئة [SmartPtr](../smartptr/)
* الهيكل [IsExceptionWrapper](../isexceptionwrapper/)
* المجال [System](../)
* المكتبة [Aspose.Slides](../../)