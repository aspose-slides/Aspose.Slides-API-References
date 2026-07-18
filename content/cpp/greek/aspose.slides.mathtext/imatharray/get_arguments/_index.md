---
title: get_Arguments()
second_title: Aspose.Slides για C++ API Αναφορά
description: Το σύνολο των στοιχείων του πίνακα
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() μέθοδος

Το σύνολο των στοιχείων του πίνακα

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
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
* Κλάση [IMathArray](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)