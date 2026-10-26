---
title: get_Base()
second_title: Aspose.Slides für C++ API-Referenz
description: Funktionsargument
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() Methode


Funktionsargument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Hinweise


Beispiel: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathFunction](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)