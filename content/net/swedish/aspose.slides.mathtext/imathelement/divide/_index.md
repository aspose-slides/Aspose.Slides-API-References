---
title: Divide
second_title: Aspose.Sildes för .NET API-referens
description: Skapar ett bråk med detta täljare och specificerad nämnare
type: docs
weight: 30
url: /sv/aspose.slides.mathtext/imathelement/divide/
---
## Divide(IMathElement) {#divide}

Skapar ett bråk med detta täljare och specificerad nämnare

```csharp
public IMathFraction Divide(IMathElement denominator)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | IMathElement | Nämnare |

### Returvärde

nytt bråk

### Exempel

Exempel:

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathElement denumerator = new MathematicalText("y");
IMathFraction fraction = numerator.Divide(denumerator);
```

### Se också

* gränssnitt [IMathFraction](../../imathfraction)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

---

## Divide(string) {#divide_2}

Skapar ett bråk med detta täljare och specificerad nämnare

```csharp
public IMathFraction Divide(string denominator)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | String | Nämnare |

### Returvärde

nytt bråk

### Exempel

Exempel:

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathFraction fraction = numerator.Divide("y");
```

### Se också

* gränssnitt [IMathFraction](../../imathfraction)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

---

## Divide(IMathElement, MathFractionTypes) {#divide_1}

Skapar ett bråk av den angivna typen med detta täljare och specificerad nämnare

```csharp
public IMathFraction Divide(IMathElement denominator, MathFractionTypes fractionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | IMathElement | Nämnare |
| fractionType | MathFractionTypes | Bråktyp: Bar, NoBar, Skewed, Linear |

### Returvärde

nytt bråk

### Exempel

Exempel:

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathElement denumerator = new MathematicalText("y");
IMathFraction fraction = numerator.Divide(denumerator, MathFractionTypes.Linear);
```

### Se också

* gränssnitt [IMathFraction](../../imathfraction)
* enum [MathFractionTypes](../../mathfractiontypes)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

---

## Divide(string, MathFractionTypes) {#divide_3}

Skapar ett bråk av den angivna typen med detta täljare och specificerad nämnare

```csharp
public IMathFraction Divide(string denominator, MathFractionTypes fractionType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| denominator | String | Nämnare |
| fractionType | MathFractionTypes | Bråktyp: Bar, NoBar, Skewed, Linear |

### Returvärde

nytt bråk

### Exempel

Exempel:

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathFraction fraction = numerator.Divide("y", MathFractionTypes.Linear);
```

### Se också

* gränssnitt [IMathFraction](../../imathfraction)
* enum [MathFractionTypes](../../mathfractiontypes)
* gränssnitt [IMathElement](../../imathelement)
* namnrymd [Aspose.Slides.MathText](../../imathelement)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: genererad av xmldocmd för Aspose.Slides.dll -->