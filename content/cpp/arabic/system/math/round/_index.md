---
title: Round()
second_title: Aspose.Slides للـ C++ - مرجع API
description: يقرب القيمة المحددة إلى أقرب قيمة صحيحة.
type: docs
weight: 157
url: /ar/system/math/round/
---
## Math::Round(double) طريقة


يقوم بتقريب القيمة المحددة إلى أقرب قيمة صحيحة.

```cpp
static double System::Math::Round(double a)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| a | **double** | القيمة التي سيتم تقريبها |

### قيمة الإرجاع

**a** تقريب إلى أقرب قيمة صحيحة

## Math::Round(double, int) طريقة


يقوم بتقريب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية.

```cpp
static double System::Math::Round(double value, int digits)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **double** | القيمة التي سيتم تقريبها |
| digits | int | عدد الأرقام العشرية في القيمة المقربة |

### قيمة الإرجاع

العدد بعدد الأرقام المحدد الأقرب إلى **value**

## Math::Round(double, MidpointRounding) طريقة


يقوم بتقريب القيمة المحددة إلى أقرب عدد صحيح. يحدد أحد المعاملات سلوك الدالة إذا كانت القيمة المحددة متساوية القرب لأقرب عددين.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **double** | القيمة التي سيتم تقريبها |
| mode | [MidpointRounding](../../midpointrounding/) | يحدد كيف يتم التقريب إذا كانت **value** متساوية القرب لأقرب عددين. |

### قيمة الإرجاع

**value** تقريب إلى أقرب قيمة صحيحة

## Math::Round(double, int, MidpointRounding) طريقة


يقوم بتقريب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية. يحدد أحد المعاملات سلوك الدالة إذا كانت القيمة المحددة متساوية القرب لأقرب عددين.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | **double** | القيمة التي سيتم تقريبها |
| digits | int | عدد الأرقام العشرية في القيمة المقربة |
| mode | [MidpointRounding](../../midpointrounding/) | يحدد كيف يتم التقريب إذا كانت **value** متساوية القرب لأقرب عددين. |

### قيمة الإرجاع

العدد بعدد الأرقام المحدد الأقرب إلى **value**

## Math::Round(const Decimal\&) طريقة


يقوم بتقريب القيمة المحددة إلى أقرب قيمة صحيحة.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | القيمة التي سيتم تقريبها |

### قيمة الإرجاع

**d** تقريب إلى أقرب قيمة صحيحة

## Math::Round(const Decimal\&, int) طريقة


يقوم بتقريب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | القيمة التي سيتم تقريبها |
| digits | int | عدد الأرقام العشرية في القيمة المقربة |

### قيمة الإرجاع

العدد بعدد الأرقام المحدد الأقرب إلى **value**

## Math::Round(const Decimal\&, MidpointRounding) طريقة


يقوم بتقريب القيمة المحددة إلى أقرب عدد صحيح. يحدد أحد المعاملات سلوك الدالة إذا كانت القيمة المحددة متساوية القرب لأقرب عددين.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | القيمة التي سيتم تقريبها |
| mode | [MidpointRounding](../../midpointrounding/) | يحدد كيف يتم التقريب إذا كانت **value** متساوية القرب لأقرب عددين. |

### قيمة الإرجاع

**d** تقريب إلى أقرب قيمة صحيحة

## Math::Round(const Decimal\&, int, MidpointRounding) طريقة


يقوم بتقريب القيمة المحددة إلى أقرب قيمة بعدد محدد من الأرقام العشرية. يحدد أحد المعاملات سلوك الدالة إذا كانت القيمة المحددة متساوية القرب لأقرب عددين.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | القيمة التي سيتم تقريبها |
| digits | int | عدد الأرقام العشرية في القيمة المقربة |
| mode | [MidpointRounding](../../midpointrounding/) | يحدد كيف يتم التقريب إذا كانت **value** متساوية القرب لأقرب عددين. |

### قيمة الإرجاع

العدد بعدد الأرقام المحدد الأقرب إلى **value**

## انظر أيضاً

* تعداد [MidpointRounding](../../midpointrounding/)
* فئة [Decimal](../../decimal/)
* بنية [Math](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)