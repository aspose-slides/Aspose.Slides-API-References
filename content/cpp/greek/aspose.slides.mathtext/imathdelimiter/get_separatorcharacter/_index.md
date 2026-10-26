---
title: get_SeparatorCharacter()
second_title: Αναφορά API Aspose.Slides για C++
description: "Ο χαρακτήρας διαχωριστικού καθορίζει το χαρακτήρα που χωρίζει τα ορίσματα στο αντικείμενο διαχωριστικού. Η προεπιλογή: '|'."
type: docs
weight: 40
url: /el/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() method

Το Χαρακτήρας Διαχωριστικού Προσδιορίζει το χαρακτήρα που χωρίζει τα ορίσματα στο αντικείμενο διαχωριστικού. Η προεπιλογή: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
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