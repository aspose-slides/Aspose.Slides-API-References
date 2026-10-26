---
title: Add()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσθέτει IMathBlock στο τέλος της συλλογής.
type: docs
weight: 92
url: /el/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) method

Προσθέτει [IMathBlock](../../imathblock/) στο τέλος της συλλογής.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Ένα μαθηματικό μπλοκ που θα προστεθεί στο τέλος της συλλογής |
## Παρατηρήσεις

Παράδειγμα:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [MathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)