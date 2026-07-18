---
title: get_BeginningCharacter()
second_title: Αναφορά API Aspose.Slides για C++
description: "Το χαρακτηριστικό Delimiter Beginning Character καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και αγκύλες. Η προεπιλεγμένη τιμή: '('."
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() μέθοδος

Το χαρακτηριστικό Delimiter Beginning Character καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και αγκύλες. Η προεπιλεγμένη τιμή: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Δείτε επίσης

* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)