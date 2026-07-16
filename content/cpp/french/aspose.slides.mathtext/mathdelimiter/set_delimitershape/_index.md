---
title: set_DelimiterShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque MathDelimiterShape::Centered, les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et sont toujours ajustés pour correspondre à toute la hauteur de leurs contenus. Lorsque MathDelimiterShape::Match, leur hauteur et leur forme sont modifiées pour correspondre exactement à leurs contenus."
type: docs
weight: 131
url: /fr/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) méthode


Spécifie la forme des délimiteurs dans l'objet délimiteur. Lorsque [MathDelimiterShape::Centered](../../mathdelimitershape/), les délimiteurs sont centrés autour de l'axe mathématique du texte mathématique et sont toujours ajustés pour correspondre à toute la hauteur de leur contenu. Lorsque [MathDelimiterShape::Match](../../mathdelimitershape/), leur hauteur et leur forme sont modifiées pour correspondre exactement à leur contenu.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## Remarques


Exemple : 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## Voir aussi

* Énum [MathDelimiterShape](../../mathdelimitershape/)
* Classe [MathDelimiter](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)