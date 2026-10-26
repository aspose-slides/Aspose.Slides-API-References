---
title: MathPortion()
second_title: Aspose.Slides dla C++ - referencja API
description: Inicjalizuje nową instancję klasy MathPortion.
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() konstruktor


Inicjalizuje nową instancję klasy [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Uwagi


Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Zobacz także

* Klasa [MathPortion](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)