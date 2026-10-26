---
title: get_Base()
second_title: Aspose.Slides για C++ API Αναφορά
description: Base παράμετρος
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() μέθοδος


Base παράμετρος

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## Σχόλια


Παράδειγμα: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathPhantom](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)