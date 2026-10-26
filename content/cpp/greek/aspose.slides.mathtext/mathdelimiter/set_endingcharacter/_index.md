---
title: set_EndingCharacter()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ο χαρακτήρας λήξης του διαχωριστικού καθορίζει τον χαρακτήρα λήξης ή κλεισίματος. Τα μαθηματικά διαχωριστικά είναι χαρακτήρες που περιβάλλουν, όπως οι παρενθέσεις, οι αγκύλες και οι άγκυλες. Η προεπιλογή: ')'."
type: docs
weight: 79
url: /el/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) μέθοδος

Delimiter Ending Character καθορίζει τον χαρακτήρα λήξης ή κλεισίματος του διαχωριστικού. Τα μαθηματικά διαχωριστικά είναι χαρακτήρες εγκλεισμού όπως οι παρενθέσεις, οι αγκύλες και οι άγκυλες. Η προεπιλογή: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Δείτε επίσης

* Τάξη [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)