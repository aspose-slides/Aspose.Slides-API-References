---
title: set_BaseJustification()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμίζεται με το κάτω μέρος, την κορυφή ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center"
type: docs
weight: 27
url: /el/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) μέθοδος

Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμίζεται με το κάτω μέρος, την κορυφή ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Δείτε επίσης

* Απαρίθμηση [MathVerticalAlignment](../../mathverticalalignment/)
* Κλάση [IMathArray](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)