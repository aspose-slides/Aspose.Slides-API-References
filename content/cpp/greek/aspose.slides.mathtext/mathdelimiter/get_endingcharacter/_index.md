---
title: get_EndingCharacter()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Το Delimiter Ending Character καθορίζει τον τελικό, ή κλείσιμο, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και αγκυβόλες. Η προεπιλογή: ')'."
type: docs
weight: 66
url: /el/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() μέθοδος

Delimiter Ending Character καθορίζει τον τελικό, ή κλείσιμο, χαρακτήρα οριοθέτη. Τα μαθηματικά οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και αγκυβόλες. Η προεπιλογή: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Δείτε επίσης

* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)