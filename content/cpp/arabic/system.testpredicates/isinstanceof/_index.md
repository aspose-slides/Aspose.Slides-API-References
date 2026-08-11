---
title: IsInstanceOf()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم Is-instance-of بمقارنة المعاملات لتصريح IsInstanceOf.
type: docs
weight: 118
url: /ar/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) دالة

Is-instance-of يقارن الوسائط لتصريح IsInstanceOf.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع الوسيط. |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| lhs_expr | const char * | تعبير الطرف الأيسر. |
| rhs_expr | const char * | تعبير الطرف الأيمن. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | كائن typeInfo يمثل نوعًا يتم مقارنة نوع **obj** معه |
| obj | const T\& | كائن يتم مقارنة نوعه مع النوع المحدد |

### قيمة الإرجاع

نتيجة التأكيد بنمط gtest.

## انظر أيضًا

* الفئة [TypeInfo](../../system/typeinfo/)
* المساحة الاسمية [System::TestPredicates](../)
* المكتبة [Aspose.Slides](../../)