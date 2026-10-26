---
title: get_Base()
second_title: Αναφορά API Aspose.Slides για C++
description: Βασική παράμετρος
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathgroupingcharacter/get_base/
---
## IMMathGroupingCharacter::get_Base() μέθοδος


Βασική παράμετρος

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathGroupingCharacter::get_Base()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathGroupingCharacter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)