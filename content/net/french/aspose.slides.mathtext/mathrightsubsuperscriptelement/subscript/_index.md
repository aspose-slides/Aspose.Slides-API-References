---
title: Subscript
second_title: Référence de l'API Aspose.Slides pour .NET
description: Argument dindice
type: docs
weight: 30
url: /fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/
---
## MathRightSubSuperscriptElement.Subscript property

Argument d'indice

```csharp
public IMathElement Subscript { get; }
```

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sub = subsuperscript.Subscript;
```

### Voir également

* interface [IMathElement](../../imathelement)
* class [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* espace de noms [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
