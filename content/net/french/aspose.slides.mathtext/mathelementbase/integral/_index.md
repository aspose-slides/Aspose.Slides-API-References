---
title: Integral
second_title: Référence API Aspose.Slides pour .NET
description: Prend l'intégrale
type: docs
weight: 70
url: /fr/aspose.slides.mathtext/mathelementbase/integral/
---

## Intégrale(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Prend l'intégrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type d'intégrale |
| lowerLimit | IMathElement | Limite inférieure de l'intégrale |
| upperLimit | IMathElement | Limite supérieure de l'intégrale |
| limitLocations | MathLimitLocations | Emplacement des limites |

### Valeur de retour

Nouvelle instance de type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Intégrale(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Prend l'intégrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type d'intégrale |
| lowerLimit | IMathElement | Limite inférieure de l'intégrale |
| upperLimit | IMathElement | Limite supérieure de l'intégrale |

### Valeur de retour

Nouvelle instance de type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Intégrale(MathIntegralTypes) {#integral}

Prend l'intégrale sans limites

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type d'intégrale |

### Valeur de retour

Nouvelle instance de type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Intégrale(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Prend l'intégrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type d'intégrale |
| lowerLimit | String | Limite inférieure de l'intégrale |
| upperLimit | String | Limite supérieure de l'intégrale |
| limitLocations | MathLimitLocations | Emplacement des limites |

### Valeur de retour

Nouvelle instance de type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

---

## Intégrale(MathIntegralTypes, string, string) {#integral_3}

Prend l'intégrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type d'intégrale |
| lowerLimit | String | Limite inférieure de l'intégrale |
| upperLimit | String | Limite supérieure de l'intégrale |

### Valeur de retour

Nouvelle instance de type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* class [MathElementBase](../../mathelementbase)
* namespace [Aspose.Slides.MathText](../../mathelementbase)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->