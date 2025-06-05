---
title: LimitLocation
second_title: Aspose.Slides pour la référence de l'API .NET
description: L'emplacement des limites en indice et surindice
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathnaryoperatorproperties/limitlocation/
---

## IMathNaryOperatorProperties.LimitLocation propriété

L'emplacement des limites (indice et surindice)

```csharp
public MathLimitLocations LimitLocation { get; set; }
```

### Exemples

Exemple:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
naryOperator.LimitLocation = MathLimitLocations.SubscriptSuperscript;
```

### Voir Aussi

* enum [MathLimitLocations](../../mathlimitlocations)
* interface [IMathNaryOperatorProperties](../../imathnaryoperatorproperties)
* namespace [Aspose.Slides.MathText](../../imathnaryoperatorproperties)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->
