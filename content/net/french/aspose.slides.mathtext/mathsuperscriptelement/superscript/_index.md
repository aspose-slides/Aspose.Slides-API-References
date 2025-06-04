---
title: Superscript
second_title: Aspose.Sildes pour .NET Référence API
description: Superscript
type: docs
weight: 20
url: /fr/aspose.slides.mathtext/mathsuperscriptelement/superscript/
---

## MathSuperscriptElement.Superscript propriété

Superscript

```csharp
public IMathElement Superscript { get; }
```

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement superscript = new MathematicalText("i");
MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
IMathElement super = superscriptElement.Superscript;
```

### Voir aussi

* interface [IMathElement](../../imathelement)
* class [MathSuperscriptElement](../../mathsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../mathsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->