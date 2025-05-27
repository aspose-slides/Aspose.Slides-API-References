---
title: DelimiterShape
second_title: Aspose.Slides pour .NET API Référence
description: Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent encore être ajustés pour s'adapter à la hauteur totale de leur contenu. Lorsque MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.
type: docs
weight: 40
url: /fr/aspose.slides.mathtext/imathdelimiter/delimitershape/
---

## Propriété IMathDelimiter.DelimiterShape

Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque MathDelimiterShape.Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent encore être ajustés pour s'adapter à la hauteur totale de leur contenu. Lorsque MathDelimiterShape.Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.

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

### Voir aussi

* enum [MathDelimiterShape](../../mathdelimitershape)
* interface [IMathDelimiter](../../imathdelimiter)
* namespace [Aspose.Slides.MathText](../../imathdelimiter)
* assembly [Aspose.Slides](../../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->