---
title: get_Base()
second_title: Αναφορά API Aspose.Slides για C++
description: Το όρισμα στο οποίο εφαρμόστηκε η προφορά
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() μέθοδος

Το όρισμα στο οποίο εφαρμόστηκε η προφορά

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathAccent](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)