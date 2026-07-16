---
title: MathPortion()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe MathPortion.
type: docs
weight: 14
url: /fr/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() constructeur


Initialise une nouvelle instance de la classe [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Remarques


Exemple :
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Voir aussi

* Classe [MathPortion](../)
* Espace de noms [Aspose::Slides::MathText](../../)
* Bibliothèque [Aspose.Slides](../../../)