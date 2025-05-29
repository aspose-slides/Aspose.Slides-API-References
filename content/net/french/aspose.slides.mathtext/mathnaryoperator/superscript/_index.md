---
title: Exposant
second_title: Référence API Aspose.Slides pour .NET
description: Spécifie un argument d'exposant qui, par exemple, dans le cas d'une intégrale, définit la limite supérieure
type: docs
weight: 90
url: /fr/aspose.slides.mathtext/mathnaryoperator/superscript/
---

## Propriété MathNaryOperator.Superscript

Spécifie un argument d'exposant qui, par exemple, dans le cas d'une intégrale, définit la limite supérieure

```csharp
public IMathElement Superscript { get; }
```

### Exemples

Exemple :

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
IMathElement superscriptArg = naryOperator.Superscript;
```

### Voir aussi

* interface [IMathElement](../../imathelement)
* class [MathNaryOperator](../../mathnaryoperator)
* namespace [Aspose.Slides.MathText](../../mathnaryoperator)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->