---
title: get_Arguments()
second_title: Αναφορά API για Aspose.Slides για C++
description: Το σύνολο των στοιχείων του πίνακα
type: docs
weight: 1
url: /el/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() μέθοδος


Το σύνολο των στοιχείων του πίνακα

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElementCollection](../../imathelementcollection/)
* Κλάση [MathArray](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)