---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Καθορίζει την ανάπτυξη των BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, οι διαχωριστές μεγαλώνουν κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλεγμένη τιμή είναι true
type: docs
weight: 92
url: /el/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() μέθοδος

Καθορίζει την ανάπτυξη των BeginningCharacter, SeparatorCharacter, EndingCharacter Όταν true, οι οριοθέτες μεγαλώνουν κατακόρυφα ώστε να ταιριάζουν με το ύψος του τελεστή τους. Η προεπιλεγμένη τιμή είναι true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Δείτε επίσης

* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)