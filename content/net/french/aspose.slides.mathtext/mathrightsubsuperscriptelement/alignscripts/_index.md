---
title: AlignScripts
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie l'alignement du sous-script/super-script. Lorsqu'il est vrai, le sous-script et le super-script sont alignés horizontalement l'un par rapport à l'autre. Lorsqu'il est faux, ils sont ajustés à la forme de la base. La valeur par défaut est fausse.
type: docs
weight: 20
url: /fr/aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts/
---

## MathRightSubSuperscriptElement.AlignScripts propriété

Spécifie l'alignement du sous-script/super-script. Lorsqu'il est vrai, le sous-script et le super-script sont alignés horizontalement l'un par rapport à l'autre. Lorsqu'il est faux, ils sont ajustés à la forme de la base. La valeur par défaut est fausse.

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

* classe [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* espace de noms [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour Aspose.Slides.dll -->