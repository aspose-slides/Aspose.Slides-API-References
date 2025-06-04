---
title: Integral
second_title: Aspose.Sildes para .NET Referencia de API
description: Toma la integral
type: docs
weight: 80
url: /es/aspose.slides.mathtext/imathelement/integral/
---

## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Toma la integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo de integral |
| lowerLimit | IMathElement | Límite inferior de la integral |
| upperLimit | IMathElement | Límite superior de la integral |
| limitLocations | MathLimitLocations | Ubicación de los límites |

### Valor de Retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Véase También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblaje [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Toma la integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo de integral |
| lowerLimit | IMathElement | Límite inferior de la integral |
| upperLimit | IMathElement | Límite superior de la integral |

### Valor de Retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Véase También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblaje [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Toma la integral sin límites

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo de integral |

### Valor de Retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Véase También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblaje [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Toma la integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo de integral |
| lowerLimit | String | Límite inferior de la integral |
| upperLimit | String | Límite superior de la integral |
| limitLocations | MathLimitLocations | Ubicación de los límites |

### Valor de Retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Véase También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblaje [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Toma la integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo de integral |
| lowerLimit | String | Límite inferior de la integral |
| upperLimit | String | Límite superior de la integral |

### Valor de Retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Véase También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfaz [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* ensamblaje [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->