---
title: RoundImpl()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتقريب القيمة المحددة إلى أقرب قيمة مع عدد الأرقام العشرية المحدد. يحدد أحد المعاملات سلوك الدالة إذا كانت القيمة المحددة متقاربة بنفس المسافة من رقمين أقرب.
type: docs
weight: 287
url: /ar/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) طريقة

يقوم بتقريب القيمة المحددة إلى أقرب قيمة مع عدد الأرقام العشرية المحدد. يحدد أحد المعاملات سلوك الدالة إذا كانت القيمة المحددة متقاربة بنفس المسافة من رقمين أقرب.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **float** | القيمة التي سيتم تقريبها |
| digits | int | عدد الأرقام العشرية في القيمة المقربة |
| mode | [MidpointRounding](../../midpointrounding/) | يحدد كيفية تنفيذ التقريب إذا كانت **value** متقربة بنفس المسافة من رقمين أقرب. |

### قيمة الإرجاع

العدد ذو عدد الأرقام المحدد الأقرب إلى **value**

## راجع أيضًا

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)