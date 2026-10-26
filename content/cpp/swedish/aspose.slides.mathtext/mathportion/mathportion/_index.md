---
title: MathPortion()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av klassen MathPortion.
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() konstruktor

Initierar en ny instans av klassen [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Anmärkningar

Exempel:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Se även

* Klass [MathPortion](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)