---
title: Integral
second_title: Aspose.Slides dla .NET – dokumentacja API
description: Pobiera całkę
type: docs
weight: 70
url: /pl/aspose.slides.mathtext/mathelementbase/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Pobiera całkę

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ całki |
| lowerLimit | IMathElement | Dolna granica całki |
| upperLimit | IMathElement | Górna granica całki |
| limitLocations | MathLimitLocations | lokalizacja granic |

### Wartość zwracana

Nowa instancja typu [`IMathNaryOperator`](../../imathnaryoperator)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Zobacz także

* interfejs [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfejs [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Pobiera całkę

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ całki |
| lowerLimit | IMathElement | Dolna granica całki |
| upperLimit | IMathElement | Górna granica całki |

### Wartość zwracana

Nowa instancja typu [`IMathNaryOperator`](../../imathnaryoperator)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Zobacz także

* interfejs [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interfejs [IMathElement](../../imathelement)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Pobiera całkę bez granic

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ całki |

### Wartość zwracana

Nowa instancja typu [`IMathNaryOperator`](../../imathnaryoperator)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Zobacz także

* interfejs [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Pobiera całkę

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ całki |
| lowerLimit | String | Dolna granica całki |
| upperLimit | String | Górna granica całki |
| limitLocations | MathLimitLocations | lokalizacja granic |

### Wartość zwracana

Nowa instancja typu [`IMathNaryOperator`](../../imathnaryoperator)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Zobacz także

* interfejs [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Pobiera całkę

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| integralType | MathIntegralTypes | Typ całki |
| lowerLimit | String | Dolna granica całki |
| upperLimit | String | Górna granica całki |

### Wartość zwracana

Nowa instancja typu [`IMathNaryOperator`](../../imathnaryoperator)

### Przykłady

Przykład:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Zobacz także

* interfejs [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* klasa [MathElementBase](../../mathelementbase)
* przestrzeń nazw [Aspose.Slides.MathText](../../mathelementbase)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->