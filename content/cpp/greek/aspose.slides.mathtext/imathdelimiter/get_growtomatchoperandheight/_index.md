---
title: get_GrowToMatchOperandHeight()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει την ανάπτυξη του BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα διαχωριστικά αυξάνονται κάθετα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλεγμένη τιμή είναι true
type: docs
weight: 92
url: /el/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() μέθοδος

Καθορίζει την ανάπτυξη του BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα διαχωριστικά μεγαλώνουν κάθετα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλεγμένη τιμή είναι true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Δείτε επίσης

* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)