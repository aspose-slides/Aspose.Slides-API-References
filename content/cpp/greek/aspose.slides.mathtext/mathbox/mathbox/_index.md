---
title: MathBox()
second_title: Αναφορά API Aspose.Slides για C++
description: Αρχικοποιεί το MathBox με το καθορισμένο στοιχείο ως όρισμα
type: docs
weight: 144
url: /el/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) constructor

Αρχικοποιεί το [MathBox](../) με το καθορισμένο στοιχείο ως όρισμα

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό στοιχείο στο οποίο εφαρμόζεται το κουτί. Μπορεί να είναι null. |

## Σχόλια

Παράδειγμα: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathBox](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)