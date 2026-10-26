---
title: Integral
second_title: Tham chiếu API Aspose.Sildes cho .NET
description: Thực hiện tích phân
type: docs
weight: 70
url: /vi/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Thực hiện tích phân

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |
| limitLocations | MathLimitLocations | location of limits |

### Giá trị trả về

Một thể hiện mới của kiểu [`IMathNaryOperator`](../../imathnaryoperator)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Xem thêm

* giao diện [IMathNaryOperator](../../imathnaryoperator)
* liệt kê [MathIntegralTypes](../../mathintegraltypes)
* giao diện [IMathElement](../../imathelement)
* liệt kê [MathLimitLocations](../../mathlimitlocations)
* lớp [MathElementBase](../../mathelementbase)
* không gian tên [Aspose.Slides.MathText](../../mathelementbase)
* tập hợp [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Thực hiện tích phân

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |

### Giá trị trả về

Một thể hiện mới của kiểu [`IMathNaryOperator`](../../imathnaryoperator)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Xem thêm

* giao diện [IMathNaryOperator](../../imathnaryoperator)
* liệt kê [MathIntegralTypes](../../mathintegraltypes)
* giao diện [IMathElement](../../imathelement)
* lớp [MathElementBase](../../mathelementbase)
* không gian tên [Aspose.Slides.MathText](../../mathelementbase)
* tập hợp [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Thực hiện tích phân không có giới hạn

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |

### Giá trị trả về

Một thể hiện mới của kiểu [`IMathNaryOperator`](../../imathnaryoperator)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Xem thêm

* giao diện [IMathNaryOperator](../../imathnaryoperator)
* liệt kê [MathIntegralTypes](../../mathintegraltypes)
* lớp [MathElementBase](../../mathelementbase)
* không gian tên [Aspose.Slides.MathText](../../mathelementbase)
* tập hợp [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Thực hiện tích phân

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |
| limitLocations | MathLimitLocations | location of limits |

### Giá trị trả về

Một thể hiện mới của kiểu [`IMathNaryOperator`](../../imathnaryoperator)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Xem thêm

* giao diện [IMathNaryOperator](../../imathnaryoperator)
* liệt kê [MathIntegralTypes](../../mathintegraltypes)
* liệt kê [MathLimitLocations](../../mathlimitlocations)
* lớp [MathElementBase](../../mathelementbase)
* không gian tên [Aspose.Slides.MathText](../../mathelementbase)
* tập hợp [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Thực hiện tích phân

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |

### Giá trị trả về

Một thể hiện mới của kiểu [`IMathNaryOperator`](../../imathnaryoperator)

### Ví dụ

Ví dụ:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Xem thêm

* giao diện [IMathNaryOperator](../../imathnaryoperator)
* liệt kê [MathIntegralTypes](../../mathintegraltypes)
* lớp [MathElementBase](../../mathelementbase)
* không gian tên [Aspose.Slides.MathText](../../mathelementbase)
* tập hợp [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->