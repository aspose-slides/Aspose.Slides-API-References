---
title: set_BeginningCharacter()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ο Χαρακτήρας Αρχής Οριοδείκτη καθορίζει την αρχή, ή το άνοιγμα, του χαρακτήρα οριοδείκτη. Οι μαθηματικοί οριοδείκτες είναι χαρακτήρες περιέλειψης όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλεγμένη τιμή: '('."
type: docs
weight: 27
url: /el/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) μέθοδος

Το Χαρακτήρας Αρχής Οριοδείκτη καθορίζει την αρχή, ή το άνοιγμα, του χαρακτήρα οριοδείκτη. Οι μαθηματικοί οριοδείκτες είναι χαρακτήρες περιέλειψης όπως παρενθέσεις, αγκύλες και άγκιστρα. Η προεπιλεγμένη τιμή: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Σχόλια

Παράδειγμα:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Δείτε επίσης

* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)