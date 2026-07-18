---
title: get_Base()
second_title: Aspose.Slides για C++ API Αναφορά
description: Base παράμετρος
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() μέθοδος


Base παράμετρος

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
```

## Σχόλια


Παράδειγμα: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathPhantom](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)