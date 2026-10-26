---
title: set_SeparatorCharacter()
second_title: Αναφορά API Aspose.Slides για C++
description: "Το Delimiter Separator Character καθορίζει το χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο delimiter. Η προεπιλογή: '|'."
type: docs
weight: 53
url: /el/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) μέθοδος


Το Delimiter Separator Character καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο delimiter. Η προεπιλογή: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Δείτε επίσης

* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)