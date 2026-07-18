---
title: set_SeparatorCharacter()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Το Delimiter Separator Character καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο delimiter. Η προεπιλογή: '|'."
type: docs
weight: 53
url: /el/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) μέθοδος

Delimiter Separator Character καθορίζει τον χαρακτήρα που διαχωρίζει τα ορίσματα στο αντικείμενο delimiter. Η προεπιλογή: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
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