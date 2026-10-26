---
title: Integral
second_title: Riferimento API Aspose.Sildes per .NET
description: Esegue l'integrale
type: docs
weight: 80
url: /it/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Esegue l'integrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo di integrale |
| lowerLimit | IMathElement | Limite inferiore dell'integrale |
| upperLimit | IMathElement | Limite superiore dell'integrale |
| limitLocations | MathLimitLocations | posizione dei limiti |

### Valore restituito

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
* enumerazione [MathIntegralTypes](../../mathintegraltypes)
* enumerazione [MathLimitLocations](../../mathlimitlocations)
* interfaccia [IMathElement](../../imathelement)
* spazio dei nomi [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Esegue l'integrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo di integrale |
| lowerLimit | IMathElement | Limite inferiore dell'integrale |
| upperLimit | IMathElement | Limite superiore dell'integrale |

### Valore restituito

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
* enumerazione [MathIntegralTypes](../../mathintegraltypes)
* interfaccia [IMathElement](../../imathelement)
* spazio dei nomi [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Esegue l'integrale senza limiti

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo di integrale |

### Valore restituito

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
* enumerazione [MathIntegralTypes](../../mathintegraltypes)
* interfaccia [IMathElement](../../imathelement)
* spazio dei nomi [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Esegue l'integrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo di integrale |
| lowerLimit | String | Limite inferiore dell'integrale |
| upperLimit | String | Limite superiore dell'integrale |
| limitLocations | MathLimitLocations | posizione dei limiti |

### Valore restituito

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
* enumerazione [MathIntegralTypes](../../mathintegraltypes)
* enumerazione [MathLimitLocations](../../mathlimitlocations)
* interfaccia [IMathElement](../../imathelement)
* spazio dei nomi [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Esegue l'integrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Tipo di integrale |
| lowerLimit | String | Limite inferiore dell'integrale |
| upperLimit | String | Limite superiore dell'integrale |

### Valore restituito

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
* enumerazione [MathIntegralTypes](../../mathintegraltypes)
* interfaccia [IMathElement](../../imathelement)
* spazio dei nomi [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->