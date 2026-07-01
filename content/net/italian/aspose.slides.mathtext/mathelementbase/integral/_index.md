---
title: Integral
second_title: Riferimento API Aspose.Sildes per .NET
description: Prende l'integrale
type: docs
weight: 70
url: /it/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Prende l'integrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integrale |
| lowerLimit | IMathElement | Limite inferiore dell'integrale |
| upperLimit | IMathElement | Limite superiore dell'integrale |
| limitLocations | MathLimitLocations | posizione dei limiti |

### Valore di ritorno

Nuova istanza del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Esempi

Esempio:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Vedi anche

* interfaccia [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfaccia [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* classe [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Prende l'integrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integrale |
| lowerLimit | IMathElement | Limite inferiore dell'integrale |
| upperLimit | IMathElement | Limite superiore dell'integrale |

### Valore di ritorno

Nuova istanza del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Esempi

Esempio:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Vedi anche

* interfaccia [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfaccia [IMathElement](../../imathelement)
* classe [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Prende l'integrale senza limiti

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integrale |

### Valore di ritorno

Nuova istanza del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Esempi

Esempio:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Vedi anche

* interfaccia [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* classe [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Prende l'integrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integrale |
| lowerLimit | String | Limite inferiore dell'integrale |
| upperLimit | String | Limite superiore dell'integrale |
| limitLocations | MathLimitLocations | posizione dei limiti |

### Valore di ritorno

Nuova istanza del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Esempi

Esempio:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Vedi anche

* interfaccia [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* classe [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Prende l'integrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo integrale |
| lowerLimit | String | Limite inferiore dell'integrale |
| upperLimit | String | Limite superiore dell'integrale |

### Valore di ritorno

Nuova istanza del tipo [`IMathNaryOperator`](../../imathnaryoperator)

### Esempi

Esempio:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Vedi anche

* interfaccia [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* classe [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->