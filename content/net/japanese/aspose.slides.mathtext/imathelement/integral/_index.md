---
title: Integral
second_title: Aspose.Sildes for .NET API リファレンス
description: 積分を取得します
type: docs
weight: 80
url: /ja/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |
| limitLocations | MathLimitLocations | location of limits |

### 戻り値

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 例

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 参照

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | IMathElement | Lower limit of integral |
| upperLimit | IMathElement | Upper limit of integral |

### 戻り値

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 例

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### 参照

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

制限なしで積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |

### 戻り値

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 例

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### 参照

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |
| limitLocations | MathLimitLocations | location of limits |

### 戻り値

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 例

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### 参照

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

積分を取得します

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Integral type |
| lowerLimit | String | Lower limit of integral |
| upperLimit | String | Upper limit of integral |

### 戻り値

New instance of type [`IMathNaryOperator`](../../imathnaryoperator)

### 例

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### 参照

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->