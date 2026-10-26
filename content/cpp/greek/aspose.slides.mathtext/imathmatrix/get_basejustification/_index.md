---
title: get_BaseJustification()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom, και center. Προεπιλογή: Center"
type: docs
weight: 53
url: /el/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() μέθοδος

Καθορίζει την κατακόρυφη στοίχιση σε σχέση με το περιβάλλον κείμενο. Πιθανές τιμές είναι top, bottom και center. Προεπιλογή: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Δείτε επίσης

* Απαρίθμηση [MathVerticalAlignment](../../mathverticalalignment/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)