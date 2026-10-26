---
title: Round()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقرب القيمة المحددة إلى أقرب عدد صحيح. يحدد معامل سلوك الدالة إذا كانت القيمة المحددة قريبة بالتساوي من رقمين أقرب.
type: docs
weight: 404
url: /ar/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) طريقة

Rounds the specified value to the nearest integral number. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| d | const [Decimal](../)\& | القيمة التي سيتم تقريبها |
| mode | [MidpointRounding](../../midpointrounding/) | تحدد كيفية تنفيذ التقريب إذا كان **value** قريبًا بالتساوي من رقمين أقرب. |

### قيمة الإرجاع

**d** تقريب إلى أقرب قيمة عددية صحيحة

## Decimal::Round(const Decimal\&, int, MidpointRounding) طريقة

Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| d | const [Decimal](../)\& | القيمة التي سيتم تقريبها |
| digits | int | عدد الأرقام العشرية في القيمة المقربة |
| mode | [MidpointRounding](../../midpointrounding/) | تحدد كيفية تنفيذ التقريب إذا كان **value** قريبًا بالتساوي من رقمين أقرب. |

### قيمة الإرجاع

العدد بعدد الأرقام المحدد الأقرب إلى **value**

## انظر أيضًا

* تعداد [MidpointRounding](../../midpointrounding/)
* فئة [Decimal](../)
* نطاق الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)