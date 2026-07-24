---
title: get_Base()
second_title: Aspose.Slides für C++ API-Referenz
description: Funktionsargument
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() Methode


Funktionsargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Anmerkungen


Beispiel: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathFunction](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)