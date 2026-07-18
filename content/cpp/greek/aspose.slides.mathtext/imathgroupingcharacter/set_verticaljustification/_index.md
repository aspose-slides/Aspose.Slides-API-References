---
title: set_VerticalJustification()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Κάθετη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας βρίσκεται πάνω από το αντικείμενο, η VerticalJustification του Top υποδεικνύει ότι το επάνω μέρος του αντικειμένου πέφτει στη γραμμή βάσης· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom"
type: docs
weight: 79
url: /el/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) μέθοδος


Κάθετη στοίχιση του χαρακτήρα ομάδας. Καθορίζει την ευθυγράμμιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομάδας είναι πάνω από το αντικείμενο, η VerticalJustification του Top υποδεικνύει ότι το επάνω μέρος του αντικειμένου πέφτει στη γραμμή βάσης· όταν η VerticalJustification ορίζεται σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης. Προεπιλογή: Bottom για Position=Top και Top για Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Δείτε επίσης

* Απαρίθμηση [MathTopBotPositions](../../mathtopbotpositions/)
* Κλάση [IMathGroupingCharacter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)