---
title: Integral
second_title: Referencia de la API de Aspose.Slides para .NET
description: Toma la integral
type: docs
weight: 70
url: /es/aspose.slides.mathtext/mathelementbase/integral/
---

## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

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
| limitLocations | MathLimitLocations | ubicación de los límites |

### Valor de retorno

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

### Ver También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfaz [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

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

### Valor de retorno

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

### Ver También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfaz [IMathElement](../../imathelement)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Toma la integral sin límites

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo de integral |

### Valor de retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Ver También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

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
| limitLocations | MathLimitLocations | ubicación de los límites |

### Valor de retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Ver También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

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

### Valor de retorno

Nueva instancia del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Ver También

* interfaz [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* clase [MathElementBase](../../mathelementbase)
* espacio de nombres [Aspose.Slides.MathText](../../mathelementbase)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->