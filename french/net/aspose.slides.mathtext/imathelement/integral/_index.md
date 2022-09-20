---
title: Integral
second_title: Référence de l'API Aspose.Slides pour .NET
description: Prend lintégrale
type: docs
weight: 80
url: /fr/net/aspose.slides.mathtext/imathelement/integral/
---
## Integral(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) {#integral_2}

Prend l'intégrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit, MathLimitLocations limitLocations)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type intégral |
| lowerLimit | IMathElement | Limite inférieure de l'intégrale |
| upperLimit | IMathElement | Limite supérieure de l'intégrale |
| limitLocations | MathLimitLocations | emplacement des limites |

### Return_Value

Nouvelle instance de type[`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, IMathElement, IMathElement) {#integral_1}

Prend l'intégrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, IMathElement lowerLimit, 
    IMathElement upperLimit)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type intégral |
| lowerLimit | IMathElement | Limite inférieure de l'intégrale |
| upperLimit | IMathElement | Limite supérieure de l'intégrale |

### Return_Value

Nouvelle instance de type[`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathElement lowerLimit = new MathematicalText("1");
IMathElement upperLimit = new MathematicalText("2");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes) {#integral}

Prend l'intégrale sans limites

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type intégral |

### Return_Value

Nouvelle instance de type[`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Contour);
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string, MathLimitLocations) {#integral_4}

Prend l'intégrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit, MathLimitLocations limitLocations)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type intégral |
| lowerLimit | String | Limite inférieure de l'intégrale |
| upperLimit | String | Limite supérieure de l'intégrale |
| limitLocations | MathLimitLocations | emplacement des limites |

### Return_Value

Nouvelle instance de type[`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

---

## Integral(MathIntegralTypes, string, string) {#integral_3}

Prend l'intégrale

```csharp
public IMathNaryOperator Integral(MathIntegralTypes integralType, string lowerLimit, 
    string upperLimit)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| integralType | MathIntegralTypes | Type intégral |
| lowerLimit | String | Limite inférieure de l'intégrale |
| upperLimit | String | Limite supérieure de l'intégrale |

### Return_Value

Nouvelle instance de type[`IMathNaryOperator`](../../imathnaryoperator)

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("𝑥");
IMathNaryOperator integral = baseElement.Integral(MathIntegralTypes.Simple, "1", "5");
```

### Voir également

* interface [IMathNaryOperator](../../imathnaryoperator)
* enum [MathIntegralTypes](../../mathintegraltypes)
* interface [IMathElement](../../imathelement)
* espace de noms [Aspose.Slides.MathText](../../imathelement)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
