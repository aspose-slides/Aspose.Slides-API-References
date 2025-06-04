---
title: Integral
second_title: Référence API Aspose.Slides pour .NET
description: Prend l'intégrale
type: docs
weight: 80
url: /fr/aspose.slides.mathtext/imathelement/integral/
---

## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

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
| limitLocations | MathLimitLocations | emplacement des limites |

### Valeur de retour

Nouvelle instance du type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Voir aussi

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

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

Nouvelle instance du type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Voir aussi

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Prend l'intégrale sans limites

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type d'intégrale |

### Valeur de retour

Nouvelle instance du type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Voir aussi

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

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
| limitLocations | MathLimitLocations | emplacement des limites |

### Valeur de retour

Nouvelle instance du type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Voir aussi

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

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

Nouvelle instance du type [`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Voir aussi

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->