---
title: MathPortion()
second_title: Aspose.Slides pro C++ – reference API
description: Inicializuje novou instanci třídy MathPortion.
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() konstruktor

Inicializuje novou instanci třídy [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Poznámky

Příklad: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Viz také

* Třída [MathPortion](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)