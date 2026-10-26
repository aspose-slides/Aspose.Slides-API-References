---
title: get_BaseJustification()
second_title: Αναφορά API Aspose.Slides για C++
description: "Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το άνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() μέθοδος

Καθορίζει την ευθυγράμμιση του πίνακα σε σχέση με το περιβάλλον κείμενο. Το κείμενο εκτός του πίνακα μπορεί να ευθυγραμμιστεί με το κάτω μέρος, το άνω μέρος ή το κέντρο ενός αντικειμένου πίνακα. Προεπιλεγμένη τιμή: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Σημειώσεις

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