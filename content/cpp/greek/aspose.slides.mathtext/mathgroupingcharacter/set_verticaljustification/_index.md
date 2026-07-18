---
title: set_VerticalJustification()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, η VerticalJustification του Top σημαίνει ότι το πάνω μέρος του αντικειμένου πέφτει στη γραμμή βάσης· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου βρίσκεται στη γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom"
type: docs
weight: 79
url: /el/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) μέθοδος

Κατακόρυφη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, η VerticalJustification του Top σημαίνει ότι το πάνω μέρος του αντικειμένου πέφτει στη γραμμή βάσης· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου βρίσκεται στη γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Δείτε επίσης

* Απαρίθμηση [MathTopBotPositions](../../mathtopbotpositions/)
* Κλάση [MathGroupingCharacter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)