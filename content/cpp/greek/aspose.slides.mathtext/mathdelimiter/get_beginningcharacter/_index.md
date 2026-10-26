---
title: get_BeginningCharacter()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Το Delimiter Beginning Character καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: '('."
type: docs
weight: 14
url: /el/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() μέθοδος

Το χαρακτηριστικό Delimiter Beginning Character καθορίζει τον αρχικό, ή ανοικτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιτύλιξης όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Σχόλια


Παράδειγμα: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```


## Δείτε επίσης

* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)