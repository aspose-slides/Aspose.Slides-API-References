---
title: get_Arguments()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτησης
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() μέθοδος

Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτησης

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Σχόλια

Παράδειγμα:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElementCollection](../../imathelementcollection/)
* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)