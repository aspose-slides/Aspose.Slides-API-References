---
title: Contains()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.
type: docs
weight: 118
url: /el/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) method


Καθορίζει εάν η συλλογή περιέχει μια συγκεκριμένη τιμή.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το αντικείμενο που πρέπει να εντοπιστεί στη συλλογή. |

### Τιμή Επιστροφής

true εάν *mathBlock* βρεθεί στη συλλογή· διαφορετικά, false.
## Σημειώσεις



Παράδειγμα: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)