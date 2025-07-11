---
title: IMathBar
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Spécifie la fonction de barre consistant en un argument de base et une barre supérieure ou inférieure
type: docs
weight: 7870
url: /fr/aspose.slides.mathtext/imathbar/
---

## Interface IMathBar

Spécifie la fonction de barre, consistant en un argument de base et une barre supérieure ou inférieure

```csharp
public interface IMathBar : IMathElement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathbar/asimathelement) { get; } | Permet d'obtenir l'interface de base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathbar/base) { get; } | Argument de base |
| [Position](../../aspose.slides.mathtext/imathbar/position) { get; set; } | Position de la ligne de barre. Par défaut : Haut |

### Exemples

Exemple:

```csharp
[C#]
IMathBar mathBar = new MathBar(new MathematicalText("x"));
```

### Voir Aussi

* interface [IMathElement](../imathelement)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
