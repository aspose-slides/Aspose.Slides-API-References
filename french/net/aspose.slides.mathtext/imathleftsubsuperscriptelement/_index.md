---
title: IMathLeftSubSuperscriptElement
second_title: Référence de l'API Aspose.Slides pour .NET
description: Spécifie lobjet SubSuperscript qui se compose dune base et dun indice et dun exposant placés à gauche de la base.
type: docs
weight: 7630
url: /fr/net/aspose.slides.mathtext/imathleftsubsuperscriptelement/
---
## IMathLeftSubSuperscriptElement interface

Spécifie l'objet Sub-Superscript, qui se compose d'une base et d'un indice et d'un exposant placés à gauche de la base.

```csharp
public interface IMathLeftSubSuperscriptElement : IMathElement
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/asimathelement) { get; } | Permet d'obtenir l'interface IMathElement de base [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/base) { get; } | Argument de base |
| [Subscript](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/subscript) { get; } | Indice |
| [Superscript](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/superscript) { get; } | Exposant |

### Exemples

Exemple :

```csharp
[C#]
IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheLeft("i", "j");
```

### Voir également

* interface [IMathElement](../imathelement)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->