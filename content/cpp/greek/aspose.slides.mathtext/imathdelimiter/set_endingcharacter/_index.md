---
title: set_EndingCharacter()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Το Delimiter Ending Character καθορίζει τον χαρακτήρα λήξης ή κλεισίματος του οριοθετικού. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιελίξεως όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: ')'."
type: docs
weight: 79
url: /el/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) μέθοδος

Delimiter Ending Character καθορίζει τον χαρακτήρα λήξης ή κλεισίματος του οριοθετικού. Οι μαθηματικοί οριοθέτες είναι χαρακτήρες περιβλήματος όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλογή: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Σχόλια

Παράδειγμα:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Δείτε επίσης

* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)