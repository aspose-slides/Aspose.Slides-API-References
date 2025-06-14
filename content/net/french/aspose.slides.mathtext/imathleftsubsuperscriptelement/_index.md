---
title: IMathLeftSubSuperscriptElement
second_title: Aspose.Sildes pour .NET Référence API
description: Spécifie l'objet Sub-Superscript qui se compose d'une base et d'un indice et d'un surindice placés à gauche de la base.
type: docs
weight: 8060
url: /fr/aspose.slides.mathtext/imathleftsubsuperscriptelement/
---

## Interface IMathLeftSubSuperscriptElement

Spécifie l'objet Sub-Superscript, qui se compose d'une base et d'un indice et d'un surindice placés à gauche de la base.

```csharp
public interface IMathLeftSubSuperscriptElement : IMathElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/asimathelement) { get; } | Permet d'obtenir l'interface de base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/base) { get; } | Argument de base |
| [Subscript](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/subscript) { get; } | Indice |
| [Superscript](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/superscript) { get; } | Surindice |

### Exemples

Exemple:

```csharp
[C#]
IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheLeft("i", "j");
```

### Voir Aussi

* interface [IMathElement](../imathelement)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->