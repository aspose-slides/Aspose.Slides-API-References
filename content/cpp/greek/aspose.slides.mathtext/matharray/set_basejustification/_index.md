---
title: set_BaseJustification()
second_title: Αναφορά API Aspose.Slides για C++
description: "Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, την κορυφή ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center"
type: docs
weight: 27
url: /el/aspose.slides.mathtext/matharray/set_basejustification/
---
## MathArray::set_BaseJustification(MathVerticalAlignment) μέθοδος

Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, την κορυφή ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Κέντρο

```cpp
void Aspose::Slides::MathText::MathArray::set_BaseJustification(MathVerticalAlignment value) override
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
* Βιβλιοθήκη [Aspose.Slides](../../../)