---
title: Integral
second_title: Aspose.Sildes สำหรับ .NET API Reference
description: รับอินทิเกรัล
type: docs
weight: 70
url: /th/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

รับอินทิเกรัล

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิเจรัล |
| lowerLimit | IMathElement | ขอบล่างของอินทิเกรัล |
| upperLimit | IMathElement | ขอบบนของอินทิเกรัล |
| limitLocations | MathLimitLocations | ตำแหน่งของขีดจำกัด |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* คลาส [MathElementBase](../../mathelementbase)
* เนมสเปซ [Aspose.Slides.MathText](../../mathelementbase)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

รับอินทิเกรัล

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิเจรัล |
| lowerLimit | IMathElement | ขอบล่างของอินทิเกรัล |
| upperLimit | IMathElement | ขอบบนของอินทิเกรัล |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* คลาส [MathElementBase](../../mathelementbase)
* เนมสเปซ [Aspose.Slides.MathText](../../mathelementbase)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

รับอินทิเกรัลโดยไม่มีขีดจำกัด

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิเจรัล |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* คลาส [MathElementBase](../../mathelementbase)
* เนมสเปซ [Aspose.Slides.MathText](../../mathelementbase)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

รับอินทิเกรัล

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิเจรัล |
| lowerLimit | String | ขอบล่างของอินทิเกรัล |
| upperLimit | String | ขอบบนของอินทิเกรัล |
| limitLocations | MathLimitLocations | ตำแหน่งของขีดจำกัด |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* คลาส [MathElementBase](../../mathelementbase)
* เนมสเปซ [Aspose.Slides.MathText](../../mathelementbase)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

รับอินทิเกรัล

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิเจรัล |
| lowerLimit | String | ขอบล่างของอินทิเกรัล |
| upperLimit | String | ขอบบนของอินทิเกรัล |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* คลาส [MathElementBase](../../mathelementbase)
* เนมสเปซ [Aspose.Slides.MathText](../../mathelementbase)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->