---
title: IMathBorderBox
second_title: Référence de l'API Aspose.Slides pour .NET
description: Dessine un rectangle ou une autre bordure autour de IMathElement.
type: docs
weight: 7490
url: /fr/net/aspose.slides.mathtext/imathborderbox/
---
## IMathBorderBox interface

Dessine un rectangle ou une autre bordure autour de IMathElement.

```csharp
public interface IMathBorderBox : IMathElement
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathborderbox/asimathelement) { get; } | Permet d'obtenir l'interface IMathElement de base [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathborderbox/base) { get; } | Argument de base |
| [HideBottom](../../aspose.slides.mathtext/imathborderbox/hidebottom) { get; set; } | Hide Bottom Edge (la valeur par défaut est false) - spécifie l'état masqué ou affiché du bord inférieur de la zone de bordure. |
| [HideLeft](../../aspose.slides.mathtext/imathborderbox/hideleft) { get; set; } | Hide Left Edge (la valeur par défaut est false) - spécifie l'état caché ou affiché du bord gauche de la bordure. |
| [HideRight](../../aspose.slides.mathtext/imathborderbox/hideright) { get; set; } | Hide Right Edge (la valeur par défaut est false) - spécifie l'état masqué ou affiché du bord droit de la zone de bordure. |
| [HideTop](../../aspose.slides.mathtext/imathborderbox/hidetop) { get; set; } | Hide Top Edge (la valeur par défaut est false) - spécifie l'état masqué ou affiché du bord supérieur de la zone de bordure. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/imathborderbox/strikethroughbottomlefttotopright) { get; set; } | Barré de bas à gauche à haut à droite (la valeur par défaut est false). Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin inférieur gauche au coin supérieur droit de la zone de bordure. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/imathborderbox/strikethroughhorizontal) { get; set; } | Horizontal barré (la valeur par défaut est false) - spécifie l'état masqué ou affiché d'une ligne horizontale barrée. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/imathborderbox/strikethroughtoplefttobottomright) { get; set; } | Strikethrough Top-Left to Bottom-Right (la valeur par défaut est false). Spécifie l'état masqué ou affiché d'une ligne diagonale barrée du coin supérieur gauche au coin inférieur droit de la zone de bordure. |
| [StrikethroughVertical](../../aspose.slides.mathtext/imathborderbox/strikethroughvertical) { get; set; } | Strikethrough Vertical (la valeur par défaut est false) - spécifie l'état masqué ou affiché d'une ligne verticale barrée. |

### Exemples

Exemple :

```csharp
[C#]
IMathBorderBox borderBox = new MathematicalText("x+y+z").ToBorderBox();
```

### Voir également

* interface [IMathElement](../imathelement)
* espace de noms [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->