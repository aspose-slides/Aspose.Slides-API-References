---
title: get_BaseJustification()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω, το άνω ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() μέθοδος

Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω, το επάνω ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Δείτε επίσης

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Κλάση [MathArray](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)