---
title: MathPortion()
second_title: Aspose.Slides für C++ API-Referenz
description: Initialisiert eine neue Instanz der MathPortion Klasse.
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() Konstruktor


Initialisiert eine neue Instanz der [MathPortion](../) Klasse.

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Bemerkungen


Beispiel: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Siehe auch

* Klasse [MathPortion](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)