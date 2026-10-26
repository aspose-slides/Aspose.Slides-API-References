---
title: MathPortion()
second_title: Aspose.Slides C++ API referencia
description: Új példányt inicializál a MathPortion osztályból.
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() konstruktor


Inicializál egy új példányt a [MathPortion](../) osztályból.

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Megjegyzések


Példa:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Lásd még

* Osztály [MathPortion](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)