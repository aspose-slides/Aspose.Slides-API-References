---
title: MathPortion()
second_title: Αναφορά API του Aspose.Slides για C++ 
description: Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MathPortion.
type: docs
weight: 14
url: /el/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() Κατασκευαστής


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## Δείτε επίσης

* Κλάση [MathPortion](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)