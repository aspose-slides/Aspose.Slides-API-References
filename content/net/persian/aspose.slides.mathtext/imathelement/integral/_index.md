---
title: Integral
second_title: مرجع API Aspose.Sildes برای .NET
description: انتگرال را می‌گیرد
type: docs
weight: 80
url: /fa/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

انتگرال را می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |
| limitLocations | MathLimitLocations | location of limits |

### مقدار بازگشت

نمونه جدید از نوع [`IMathNaryOperator`](../../imathnaryoperator)

### مثال‌ها

مثال:

```csharp
[C#]
IMMathElement baseElement = new MathematicalText("𝑥");
IMMathElement lowerLimit = new MathematicalText("1");
IMMathElement upperLimit = new MathematicalText("2");
IMMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### موارد مرتبط

* رابط [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مجوعه [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

انتگرال را می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |

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
* enum [MathIntegralTypes](../../mathintegraltypes)
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مجوعه [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

انتگرال را می‌گیرد بدون حد‌ها

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |

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
* enum [MathIntegralTypes](../../mathintegraltypes)
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مجوعه [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

انتگرال را می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |
| limitLocations | MathLimitLocations | location of limits |

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
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مجوعه [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

انتگرال را می‌گیرد

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |

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
* enum [MathIntegralTypes](../../mathintegraltypes)
* رابط [IMathElement](../../imathelement)
* فضای‌نام [Aspose.Slides.MathText](../../imathelement)
* مجوعه [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->