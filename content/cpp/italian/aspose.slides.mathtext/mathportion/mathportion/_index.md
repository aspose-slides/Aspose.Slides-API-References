---
title: MathPortion()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe MathPortion.
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() costruttore


Inizializza una nuova istanza della classe [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Osservazioni


Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Vedi anche

* Classe [MathPortion](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)