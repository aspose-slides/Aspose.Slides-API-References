---
title: Integral
second_title: Aspose.Sildes สำหรับ .NET อ้างอิง API
description: รับอินทิกรัล
type: docs
weight: 80
url: /th/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

รับอินทิกรัล

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิกรัล |
| lowerLimit | IMathElement | ขอบล่างของอินทิกรัล |
| upperLimit | IMathElement | ขอบบนของอินทิกรัล |
| limitLocations | MathLimitLocations | ตำแหน่งของขอบ |

### ค่าที่คืนกลับ

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

ตัวอย่าง:

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
* enum [MathLimitLocations](../../mathlimitlocations)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

รับอินทิกรัล

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิกรัล |
| lowerLimit | IMathElement | ขอบล่างของอินทิกรัล |
| upperLimit | IMathElement | ขอบบนของอินทิกรัล |

### ค่าที่คืนกลับ

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

ตัวอย่าง:

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
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

รับอินทิกรัลโดยไม่มีขอบ

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิกรัล |

### ค่าที่คืนกลับ

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

รับอินทิกรัล

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิกรัล |
| lowerLimit | String | ขอบล่างของอินทิกรัล |
| upperLimit | String | ขอบบนของอินทิกรัล |
| limitLocations | MathLimitLocations | ตำแหน่งของขอบ |

### ค่าที่คืนกลับ

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

รับอินทิกรัล

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | ประเภทอินทิกรัล |
| lowerLimit | String | ขอบล่างของอินทิกรัล |
| upperLimit | String | ขอบบนของอินทิกรัล |

### ค่าที่คืนกลับ

อินสแตนซ์ใหม่ของประเภท [`IMathNaryOperator`](../../imathnaryoperator)

### ตัวอย่าง

ตัวอย่าง:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### ดูเพิ่มเติม

* อินเทอร์เฟซ [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* อินเทอร์เฟซ [IMathElement](../../imathelement)
* เนมสเปซ [Aspose.Slides.MathText](../../imathelement)
* แอสเซมบลี [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->