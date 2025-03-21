---
title: Divide
second_title: Référence de l'API Aspose.Slides pour .NET
description: Crée une fraction avec ce numérateur et le dénominateur spécifié
type: docs
weight: 30
url: /fr/aspose.slides.mathtext/imathelement/divide/
---
## Divide(IMathElement) {#divide}

Crée une fraction avec ce numérateur et le dénominateur spécifié

```csharp
public IMathFraction Divide(IMathElement denominator)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| denominator | IMathElement | Dénominateur |

### Return_Value

nouvelle fraction

### Exemples

Exemple :

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathElement denumerator = new MathematicalText("y");
IMathFraction fraction = numerator.Divide(denumerator);
```

### Voir également

* interface [IMathFraction](../../imathfraction)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## Divide(string) {#divide_2}

Crée une fraction avec ce numérateur et le dénominateur spécifié

```csharp
public IMathFraction Divide(string denominator)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| denominator | String | Dénominateur |

### Return_Value

nouvelle fraction

### Exemples

Exemple :

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathFraction fraction = numerator.Divide("y");
```

### Voir également

* interface [IMathFraction](../../imathfraction)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## Divide(IMathElement, MathFractionTypes) {#divide_1}

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

```csharp
public IMathFraction Divide(IMathElement denominator, MathFractionTypes fractionType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| denominator | IMathElement | Dénominateur |
| fractionType | MathFractionTypes | Type de fraction : Barre, Pas de Barre, Asymétrique, Linéaire |

### Return_Value

nouvelle fraction

### Exemples

Exemple :

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathElement denumerator = new MathematicalText("y");
IMathFraction fraction = numerator.Divide(denumerator, MathFractionTypes.Linear);
```

### Voir également

* interface [IMathFraction](../../imathfraction)
* enum [MathFractionTypes](../../mathfractiontypes)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## Divide(string, MathFractionTypes) {#divide_3}

Crée une fraction du type spécifié avec ce numérateur et le dénominateur spécifié

```csharp
public IMathFraction Divide(string denominator, MathFractionTypes fractionType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| denominator | String | Dénominateur |
| fractionType | MathFractionTypes | Type de fraction : Barre, Pas de Barre, Asymétrique, Linéaire |

### Return_Value

nouvelle fraction

### Exemples

Exemple :

```csharp
[C#]
IMathElement numerator = new MathematicalText("x");
IMathFraction fraction = numerator.Divide("y", MathFractionTypes.Linear);
```

### Voir également

* interface [IMathFraction](../../imathfraction)
* enum [MathFractionTypes](../../mathfractiontypes)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
