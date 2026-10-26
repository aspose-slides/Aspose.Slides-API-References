---
title: get_Base()
second_title: Aspose.Slides για C++ API Αναφορά
description: Το όρισμα στο οποίο εφαρμόστηκε το τονικό σήμα
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() μέθοδος


Το όρισμα στο οποίο εφαρμόστηκε το τονικό σήμα

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
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
* Κλάση [IMathAccent](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)