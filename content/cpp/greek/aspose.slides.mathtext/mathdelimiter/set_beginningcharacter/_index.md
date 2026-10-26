---
title: set_BeginningCharacter()
second_title: Αναφορά API Aspose.Slides για C++
description: "Ο χαρακτήρας έναρξης οριοθέτη καθορίζει τον αρχικό, ή ανοιχτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιγράμματος όπως παρενθέσεις, αγκύλες και ακλείδες. Η προεπιλογή: '('."
type: docs
weight: 27
url: /el/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) μέθοδος

Ο χαρακτήρας έναρξης οριοθέτη καθορίζει τον αρχικό, ή ανοιχτό, χαρακτήρα οριοθέτη. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιγράμματος όπως παρενθέσεις, αγκύλες και ακλείδες. Η προεπιλογή: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Δείτε επίσης

* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)