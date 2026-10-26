---
title: MakeSharedPtr()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحويل المؤشر الخام إلى مؤشر ذكي.
type: docs
weight: 2900
url: /ar/system/makesharedptr/
---
## System::MakeSharedPtr(X *) دالة

يقوم بتحويل المؤشر الخام إلى مؤشر ذكي.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| X | نوع العنصر المستهدف. |

### معاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| p | X * | مؤشر خام إلى الكائن. |

### قيمة الإرجاع

مؤشر ذكي مشترك إلى الكائن.

## System::MakeSharedPtr(const X *) دالة

يقوم بتحويل المؤشر الخام إلى مؤشر ذكي. إصدار محمل للمؤشرات الثابتة. مفيد على سبيل المثال عند استخدام متغير 'this' في طرق C# المترجمة كـ const.

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| X | نوع العنصر المستهدف. |

### معاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| p | const X * | مؤشر خام إلى الكائن. |

### قيمة الإرجاع

مؤشر ذكي مشترك إلى الكائن.

## انظر أيضًا

* الفئة [SmartPtr](../smartptr/)
* مساحة الأسماء [System](../)
* المكتبة [Aspose.Slides](../../)