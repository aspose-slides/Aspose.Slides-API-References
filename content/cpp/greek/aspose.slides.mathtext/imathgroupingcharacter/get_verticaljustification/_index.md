---
title: get_VerticalJustification()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Κατακόρυφη ευθυγράμμιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, το VerticalJustification του Top υποδηλώνει ότι η κορυφή του αντικειμένου βρίσκεται στη γραμμή βάσης· όταν το VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom"
type: docs
weight: 66
url: /el/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() μέθοδος

Κατακόρυφή στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, VerticalJustification του Top υποδηλώνει ότι η κορυφή του αντικειμένου βρίσκεται στη γραμμή βάσης· όταν το VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Δείτε επίσης

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Κλάση [IMathGroupingCharacter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)