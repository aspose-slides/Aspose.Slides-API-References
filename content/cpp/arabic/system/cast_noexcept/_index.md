---
title: Cast_noexcept()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بالتحويل على كائنات SmartPtr.
type: docs
weight: 2497
url: /ar/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) دالة


يقوم بالتحويل على كائنات [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TTo | نوع المؤشر المستهدف. |
| TFrom | نوع المؤشر المصدر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | مؤشر المصدر. |

### قيمة الإرجاع

نتيجة التحويل إذا كان التحويل مسموحًا أو nullptr إذا لم يكن كذلك.

## انظر أيضًا

* الصنف [SmartPtr](../smartptr/)
* الهيكل [IsExceptionWrapper](../isexceptionwrapper/)
* النطاق [System](../)
* المكتبة [Aspose.Slides](../../)