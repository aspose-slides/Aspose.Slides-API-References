---
title: RemoveAt()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αφαιρεί ένα στοιχείο στον καθορισμένο δείκτη της συλλογής.
type: docs
weight: 157
url: /el/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) μέθοδος

Αφαιρεί ένα στοιχείο στον καθορισμένο δείκτη της συλλογής.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης, με βάση το μηδέν, του στοιχείου που θα αφαιρεθεί. |
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## Δείτε επίσης

* Κλάση [MathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)