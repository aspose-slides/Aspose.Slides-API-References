---
title: get_Base()
second_title: Αναφορά API Aspose.Slides για C++
description: Βασικό όρισμα
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() μέθοδος


Βασικό όρισμα

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Σχόλια


Παράδειγμα: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathBox](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)