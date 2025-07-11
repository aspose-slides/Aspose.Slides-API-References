---
title: DelimiterShape
second_title: Aspose.Slides pour .NET Référence API
description: Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque c'est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent encore être ajustés pour correspondre à la hauteur totale de leur contenu. Lorsque c'est MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/mathdelimiter/delimitershape/
---

## MathDelimiter.DelimiterShape propriété

Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque c'est MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent encore être ajustés pour correspondre à la hauteur totale de leur contenu. Lorsque c'est MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.

```csharp
public MathDelimiterShape DelimiterShape { get; set; }
```

### Exemples

Exemple:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Divide("y").Enclose();
delimiter.DelimiterShape = MathDelimiterShape.Match;
```

### Voir Aussi

* enum [MathDelimiterShape](../../mathdelimitershape)
* class [MathDelimiter](../../mathdelimiter)
* namespace [Aspose.Slides.MathText](../../mathdelimiter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->