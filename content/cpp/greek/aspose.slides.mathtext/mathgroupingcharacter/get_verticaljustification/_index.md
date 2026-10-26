---
title: get_VerticalJustification()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας βρίσκεται πάνω από το αντικείμενο, η VerticalJustification τιμής Top υποδηλώνει ότι η κορυφή του αντικειμένου βρίσκεται στη γραμμή βάσης· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης Προεπιλογή: Bottom για Position=Top, και Top για Position=Bottom"
type: docs
weight: 66
url: /el/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() μέθοδος

Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη βάση. Για παράδειγμα, όταν ο χαρακτήρας ομάδας βρίσκεται πάνω από το αντικείμενο, η VerticalJustification τιμής Top υποδηλώνει ότι η κορυφή του αντικειμένου βρίσκεται στη βάση· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη βάση. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Δείτε επίσης

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Κλάση [MathGroupingCharacter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)