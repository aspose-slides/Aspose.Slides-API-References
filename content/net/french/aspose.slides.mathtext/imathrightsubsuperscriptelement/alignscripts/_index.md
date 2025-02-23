---
title: AlignScripts
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie lalignement des indices/exposants. Lorsque vrai lindice et lexposant sont alignés horizontalement lun par rapport à lautre. Lorsque faux ils sont crénés à la forme de la base. La valeur par défaut est faux.
type: docs
weight: 10
url: /fr/aspose.slides.mathtext/imathrightsubsuperscriptelement/alignscripts/
---
## IMathRightSubSuperscriptElement.AlignScripts property

Spécifie l'alignement des indices/exposants. Lorsque vrai, l'indice et l'exposant sont alignés horizontalement l'un par rapport à l'autre. Lorsque faux, ils sont crénés à la forme de la base. La valeur par défaut est faux.

```csharp
public bool AlignScripts { get; set; }
```

### Exemples

Exemple :

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
subsuperscript.AlignScripts = true;
```

### Voir également

* interface [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* espace de noms [Aspose.Slides.MathText](../../imathrightsubsuperscriptelement)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
