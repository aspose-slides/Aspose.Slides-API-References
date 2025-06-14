---
title: SetLowerLimit
second_title: Aspose.Slides pour .NET API Reference
description: Prend la limite inférieure
type: docs
weight: 130
url: /fr/aspose.slides.mathtext/imathelement/setlowerlimit/
---

## SetLowerLimit(IMathElement) {#setlowerlimit}

Prend la limite inférieure

```csharp
public IMathLimit SetLowerLimit(IMathElement limit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | IMathElement | limite |

### Valeur de retour

Nouvelle instance de type [`IMathLimit`](../../imathlimit)

### Exemples

Exemple:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("lim");
IMathElement limitValue = new MathematicalText("𝑛→∞");
var limitElement = baseElement.SetLowerLimit(limitValue);
```

### Voir Aussi

* interface [IMathLimit](../../imathlimit)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

---

## SetLowerLimit(string) {#setlowerlimit_1}

Prend la limite inférieure

```csharp
public IMathLimit SetLowerLimit(string limit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| limit | String | limite |

### Valeur de retour

Nouvelle instance de type [`IMathLimit`](../../imathlimit)

### Exemples

Exemple:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("lim");
var limitElement = baseElement.SetLowerLimit("𝑛→∞");
```

### Voir Aussi

* interface [IMathLimit](../../imathlimit)
* interface [IMathElement](../../imathelement)
* namespace [Aspose.Slides.MathText](../../imathelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->