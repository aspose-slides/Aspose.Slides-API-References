---
title: get_DelimiterShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque MathDelimiterShape::Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et sont encore ajustés pour s'adapter à toute la hauteur de leur contenu. Lorsque MathDelimiterShape::Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu."
type: docs
weight: 118
url: /fr/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() méthode

Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque [MathDelimiterShape::Centered](../../mathdelimitershape/), les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et sont encore ajustés pour s'adapter à toute la hauteur de leur contenu. Lorsque [MathDelimiterShape::Match](../../mathdelimitershape/), leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## Remarques

Exemple :
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Voir aussi

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)