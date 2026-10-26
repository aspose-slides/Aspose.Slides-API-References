---
title: Remove()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή/>.
type: docs
weight: 105
url: /el/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) μέθοδος

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου αντικειμένου από τη συλλογή/>.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το αντικείμενο που θα αφαιρεθεί από τη συλλογή. |

### Τιμή επιστροφής

true εάν το *mathBlock* αφαιρέθηκε επιτυχώς από τη συλλογή· διαφορετικά, false. Αυτή η μέθοδος επιστρέφει επίσης false εάν το *mathBlock* δεν βρέθηκε στην αρχική συλλογή/>.

## Σχόλια



Παράδειγμα:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [MathParagraph](../)
* Χώρος ονομασίας [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)