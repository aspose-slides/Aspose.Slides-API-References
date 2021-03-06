---
title: Divide
second_title: Aspose.Sildes for .NET API Reference
description: 
type: docs
weight: 30
url: /net/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase.Divide method (1 of 4)

Creates a fraction with this numerator and specified denominator

```csharp
public IMathFraction Divide(IMathElement denominator)
```

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | IMathElement | Denominator |

## Return Value

new fraction

### Examples

Example:

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathElement denumerator = new MathematicalText("y");
IMathFraction fraction = numerator.Divide(denumerator);
```

### See Also

* interface [IMathFraction](../../imathfraction)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## MathElementBase.Divide method (2 of 4)

Creates a fraction with this numerator and specified denominator

```csharp
public IMathFraction Divide(string denominator)
```

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | String | Denominator |

## Return Value

new fraction

### Examples

Example:

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathFraction fraction = numerator.Divide("y");
```

### See Also

* interface [IMathFraction](../../imathfraction)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## MathElementBase.Divide method (3 of 4)

Creates a fraction of the specified type with this numerator and specified denominator

```csharp
public IMathFraction Divide(IMathElement denominator, MathFractionTypes fractionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | IMathElement | Denominator |
| fractionType | MathFractionTypes | Fraction type: Bar, NoBar, Skewed, Linear |

## Return Value

new fraction

### Examples

Example:

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathElement denumerator = new MathematicalText("y");
IMathFraction fraction = numerator.Divide(denumerator, MathFractionTypes.Linear);
```

### See Also

* interface [IMathFraction](../../imathfraction)
* interface [IMathElement](../../imathelement)
* enum [MathFractionTypes](../../mathfractiontypes)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## MathElementBase.Divide method (4 of 4)

Creates a fraction of the specified type with this numerator and specified denominator

```csharp
public IMathFraction Divide(string denominator, MathFractionTypes fractionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| denominator | String | Denominator |
| fractionType | MathFractionTypes | Fraction type: Bar, NoBar, Skewed, Linear |

## Return Value

new fraction

### Examples

Example:

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathFraction fraction = numerator.Divide("y", MathFractionTypes.Linear);
```

### See Also

* interface [IMathFraction](../../imathfraction)
* enum [MathFractionTypes](../../mathfractiontypes)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
