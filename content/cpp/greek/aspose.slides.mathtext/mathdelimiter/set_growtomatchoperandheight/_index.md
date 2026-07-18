---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει την αύξηση του BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα delimiters αυξάνονται κάθετα ώστε να ταιριάζουν με το ύψος του operand τους. Η προεπιλεγμένη τιμή είναι true
type: docs
weight: 105
url: /el/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) method

Καθορίζει την αύξηση του BeginningCharacter, SeparatorCharacter, EndingCharacter. Όταν είναι true, τα delimiters αυξάνονται κάθετα ώστε να ταιριάζουν με το ύψος του operand τους. Η προεπιλεγμένη τιμή είναι true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Σημειώσεις

Παράδειγμα:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Δείτε επίσης

* Τάξη [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)