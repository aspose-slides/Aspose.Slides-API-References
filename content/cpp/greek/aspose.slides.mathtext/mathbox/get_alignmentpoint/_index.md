---
title: get_AlignmentPoint()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Όταν είναι true, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλογή: false"
type: docs
weight: 92
url: /el/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() μέθοδος


Όταν είναι true, αυτός ο εξομοιωτής τελεστή λειτουργεί ως σημείο ευθυγράμμισης· δηλαδή, τα καθορισμένα σημεία ευθυγράμμισης σε άλλες εξισώσεις μπορούν να ευθυγραμμιστούν με αυτό. Προεπιλογή: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Δείτε επίσης

* Κλάση [MathBox](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)