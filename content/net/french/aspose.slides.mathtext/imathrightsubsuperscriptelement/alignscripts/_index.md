---
title: AlignScripts
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie l'alignement de l'indice/superscript. Lorsque vrai, l'indice et le superscript sont alignés horizontalement l'un par rapport à l'autre. Lorsque faux, ils sont ajustés à la forme de la base. La valeur par défaut est faux.
type: docs
weight: 10
url: /fr/aspose.slides.mathtext/imathrightsubsuperscriptelement/alignscripts/
---

## Propriété IMathRightSubSuperscriptElement.AlignScripts

Spécifie l'alignement de l'indice/superscript. Lorsque vrai, l'indice et le superscript sont alignés horizontalement l'un par rapport à l'autre. Lorsque faux, ils sont ajustés à la forme de la base. La valeur par défaut est faux.

```csharp
public bool AlignScripts { get; set; }
```

### Exemples

Exemple:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
subsuperscript.AlignScripts = true;
```

### Voir aussi

* interface [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../imathrightsubsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->