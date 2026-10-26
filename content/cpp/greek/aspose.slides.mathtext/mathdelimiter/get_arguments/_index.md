---
title: get_Arguments()
second_title: Αναφορά API Aspose.Slides για C++
description: Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτησης
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() μέθοδος


Ένα ή περισσότερα μαθηματικά στοιχεία χωρισμένα με χαρακτήρες οριοθέτησης

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElementCollection](../../imathelementcollection/)
* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)