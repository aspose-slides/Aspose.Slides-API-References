---
title: get_Base()
second_title: Aspose.Slides für C++ API Referenz
description: Basisargument
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() Methode

Base Argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Hinweise


Beispiel: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)