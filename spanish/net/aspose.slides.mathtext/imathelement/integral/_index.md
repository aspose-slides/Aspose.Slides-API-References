---
title: Integral
second_title: Referencia de la API de Aspose.Slides para .NET
description: Toma la integral
type: docs
weight: 80
url: /es/net/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Toma la integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | tipo integral |
| lowerLimit | IMathElement | Límite inferior de integral |
| upperLimit | IMathElement | Límite superior de integral |
| limitLocations | MathLimitLocations | ubicación de los límites |

### Valor_devuelto

Nueva instancia de tipo[`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Ver también

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Toma la integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | tipo integral |
| lowerLimit | IMathElement | Límite inferior de integral |
| upperLimit | IMathElement | Límite superior de integral |

### Valor_devuelto

Nueva instancia de tipo[`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Ver también

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Toma la integral sin límites

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | tipo integral |

### Valor_devuelto

Nueva instancia de tipo[`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Ver también

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Toma la integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | tipo integral |
| lowerLimit | String | Límite inferior de integral |
| upperLimit | String | Límite superior de integral |
| limitLocations | MathLimitLocations | ubicación de los límites |

### Valor_devuelto

Nueva instancia de tipo[`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Ver también

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Toma la integral

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| integralType | MathIntegralTypes | tipo integral |
| lowerLimit | String | Límite inferior de integral |
| upperLimit | String | Límite superior de integral |

### Valor_devuelto

Nueva instancia de tipo[`IMathNaryOperator`](../../imathnaryoperator)

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Ver también

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathelement)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
