---
title: Subscript
second_title: Référence de l'API Aspose.Slides pour .NET
description: Indice
type: docs
weight: 20
url: /fr/net/aspose.slides.mathtext/mathsubscriptelement/subscript/
---
## MathSubscriptElement.Subscript property

Indice

```csharp
public IMathElement Subscript { get; }
```

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
IMathElement sub = subscriptElement.Subscript;
```

### Voir également

* interface [IMathElement](../../imathelement)
* class [MathSubscriptElement](../../mathsubscriptelement)
* espace de noms [Aspose.Slides.MathText](../../mathsubscriptelement)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->