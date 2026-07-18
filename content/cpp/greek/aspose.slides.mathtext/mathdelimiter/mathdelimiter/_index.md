---
title: MathDelimiter()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αρχικοποιεί το MathDelimiter με το συγκεκριμένο στοιχείο ως μοναδικό βασικό όρισμα
type: docs
weight: 144
url: /el/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) Κατασκευαστής


Αρχικοποιεί το [MathDelimiter](../) με το συγκεκριμένο στοιχείο ως μοναδικό βασικό όρισμα

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό στοιχείο στο οποίο εφαρμόζεται το διαχωριστικό. Μπορεί να είναι null. |
## Σχόλια



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)