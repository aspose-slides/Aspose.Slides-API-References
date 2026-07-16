---
title: set_DelimiterShape()
second_title: Référence de l'API Aspose.Slides for C++
description: "Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque MathDelimiterShape::Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent toujours être adaptés pour correspondre à la hauteur totale de leur contenu. Lorsque MathDelimiterShape::Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu."
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) méthode

Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque [MathDelimiterShape::Centered](../../mathdelimitershape/), les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et peuvent toujours être ajustés pour correspondre à la hauteur totale de leur contenu. Lorsque [MathDelimiterShape::Match](../../mathdelimitershape/), leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## Remarques

Exemple:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Voir aussi

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Classe [IMathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)