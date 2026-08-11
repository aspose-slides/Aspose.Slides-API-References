---
title: Round()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتقريب القيمة المحددة إلى أقرب قيمة صحيحة.
type: docs
weight: 157
url: /ar/system/mathf/round/
---
## MathF::Round(float) طريقة

يقوم بتقريب القيمة المحددة إلى أقرب قيمة صحيحة.

```cpp
static float System::MathF::Round(float a)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| a | **float** | القيمة التي سيتم تقريبها |

### قيمة الإرجاع

**a** مقربة إلى أقرب قيمة صحيحة

## MathF::Round(float, int) طريقة

يقوم بتقريب القيمة المحددة إلى أقرب قيمة بعدد الأرقام العشرية المحدد.

```cpp
static float System::MathF::Round(float value, int digits)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | **float** | القيمة التي سيتم تقريبها |
| digits | int | عدد الأرقام العشرية في القيمة المقربة |

### قيمة الإرجاع

العدد بعدد الأرقام المحدد الأقرب إلى **value**

## MathF::Round(float, MidpointRounding) طريقة

يقوم بتقريب القيمة المحددة إلى أقرب عدد صحيح. تحدد معلمة سلوك الدالة إذا كانت القيمة المحددة على بعد مسافة متساوية من أقرب عددين.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | **float** | القيمة التي سيتم تقريبها |
| mode | [MidpointRounding](../../midpointrounding/) | يحدد طريقة إجراء التقريب إذا كانت **value** على بعد مسافة متساوية من أقرب عددين. |

### قيمة الإرجاع

**value** مقربة إلى أقرب قيمة صحيحة

## MathF::Round(float, int, MidpointRounding) طريقة

يقوم بتقريب القيمة المحددة إلى أقرب قيمة بعدد الأرقام العشرية المحدد. تحدد معلمة سلوك الدالة إذا كانت القيمة المحددة على بعد مسافة متساوية من أقرب عددين.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| value | **float** | القيمة التي سيتم تقريبها |
| digits | int | عدد الأرقام العشرية في القيمة المقربة |
| mode | [MidpointRounding](../../midpointrounding/) | يحدد طريقة إجراء التقريب إذا كانت **value** على بعد مسافة متساوية من أقرب عددين. |

### قيمة الإرجاع

العدد بعدد الأرقام المحدد الأقرب إلى **value**

## انظر أيضًا

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)