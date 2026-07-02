---
title: Integral
second_title: Aspose.Sildes برای .NET مرجع API
description: انتگرال را می‌گیرد
type: docs
weight: 70
url: /fa/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

انتگرال را می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع انتگرال |
| lowerLimit | IMathElement | حد پایین انتگرال |
| upperLimit | IMathElement | حد بالا انتگرال |
| limitLocations | MathLimitLocations | موقعیت حدود |

### مقدار بازگشت

نمونه جدید از نوع [`IMathNaryOperator`](../../imathnaryoperator)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### موارد مرتبط

* رابط [IMathNaryOperator](../../imathnaryoperator)
* شمارش [MathIntegralTypes](../../mathintegraltypes)
* رابط [IMathElement](../../imathelement)
* شمارش [MathLimitLocations](../../mathlimitlocations)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجتمع [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

انتگرال را می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع انتگرال |
| lowerLimit | IMathElement | حد پایین انتگرال |
| upperLimit | IMathElement | حد بالا انتگرال |

### مقدار بازگشت

نمونه جدید از نوع [`IMathNaryOperator`](../../imathnaryoperator)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### موارد مرتبط

* رابط [IMathNaryOperator](../../imathnaryoperator)
* شمارش [MathIntegralTypes](../../mathintegraltypes)
* رابط [IMathElement](../../imathelement)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجتمع [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

انتگرال را بدون حدود می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع انتگرال |

### مقدار بازگشت

نمونه جدید از نوع [`IMathNaryOperator`](../../imathnaryoperator)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### موارد مرتبط

* رابط [IMathNaryOperator](../../imathnaryoperator)
* شمارش [MathIntegralTypes](../../mathintegraltypes)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجتمع [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

انتگرال را می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع انتگرال |
| lowerLimit | String | حد پایین انتگرال |
| upperLimit | String | حد بالا انتگرال |
| limitLocations | MathLimitLocations | موقعیت حدود |

### مقدار بازگشت

نمونه جدید از نوع [`IMathNaryOperator`](../../imathnaryoperator)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### موارد مرتبط

* رابط [IMathNaryOperator](../../imathnaryoperator)
* شمارش [MathIntegralTypes](../../mathintegraltypes)
* شمارش [MathLimitLocations](../../mathlimitlocations)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجتمع [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

انتگرال را می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | نوع انتگرال |
| lowerLimit | String | حد پایین انتگرال |
| upperLimit | String | حد بالا انتگرال |

### مقدار بازگشت

نمونه جدید از نوع [`IMathNaryOperator`](../../imathnaryoperator)

### مثال‌ها

مثال:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### موارد مرتبط

* رابط [IMathNaryOperator](../../imathnaryoperator)
* شمارش [MathIntegralTypes](../../mathintegraltypes)
* کلاس [MathElementBase](../../mathelementbase)
* فضای‌نام [Aspose.Slides.MathText](../../mathelementbase)
* مجتمع [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->