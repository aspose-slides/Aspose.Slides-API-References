---
title: get_Base()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιχείρημα βάσης
type: docs
weight: 27
url: /el/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_base/
---
## MathLeftSubSuperscriptElement::get_Base() μέθοδος

Base ορίσμα

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Base() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathLeftSubSuperscriptElement](../)
* Χώρος ονόματος [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)