---
title: idx_get()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο ανάγνωση IMathBlock.
type: docs
weight: 40
url: /el/aspose.slides.mathtext/mathparagraph/idx_get/
---
## MathParagraph::idx_get(int32_t) μέθοδος


Λαμβάνει το στοιχείο στον καθορισμένο δείκτη. Μόνο ανάγνωση [IMathBlock](../../imathblock/).

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathParagraph::idx_get(int32_t index) override
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης του στοιχείου που θα ληφθεί |

### Τιμή Επιστροφής

Το μπλοκ ενός μαθηματικού κειμένου.
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [MathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)