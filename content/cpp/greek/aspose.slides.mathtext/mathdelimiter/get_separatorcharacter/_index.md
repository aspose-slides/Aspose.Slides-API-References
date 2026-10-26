---
title: get_SeparatorCharacter()
second_title: Αναφορά API Aspose.Slides για C++
description: "Το Delimiter Separator Character καθορίζει τον χαρακτήρα που διαχωρίζει τα επιχειρήματα στο αντικείμενο διαχωριστή. Η προεπιλογή: '|'."
type: docs
weight: 40
url: /el/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() μέθοδος

Delimiter Separator Character καθορίζει τον χαρακτήρα που διαχωρίζει τα επιχειρήματα στο αντικείμενο διαχωριστή. Η προεπιλογή: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Δείτε επίσης

* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)