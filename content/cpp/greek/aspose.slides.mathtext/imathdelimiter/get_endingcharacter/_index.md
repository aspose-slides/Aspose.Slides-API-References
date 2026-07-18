---
title: get_EndingCharacter()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ο χαρακτήρας λήξης του οριοθέτη καθορίζει τον τελικό ή κλειστό χαρακτήρα οριοθέτη. Τα μαθηματικά οριοθετικά σύμβολα είναι χαρακτήρες περιτύλιξης όπως οι παρενθέσεις, οι αγκύλες και τα άγκιστρα. Η προεπιλογή: ')'."
type: docs
weight: 66
url: /el/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() μέθοδος

Ο χαρακτήρας λήξης του οριοθέτη καθορίζει τον τελικό ή κλειστό χαρακτήρα οριοθέτη. Τα μαθηματικά οριοθετικά σύμβολα είναι χαρακτήρες περιτύλιξης όπως οι παρενθέσεις, οι αγκύλες και τα άγκιστρα. Η προεπιλογή: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Δείτε επίσης

* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)