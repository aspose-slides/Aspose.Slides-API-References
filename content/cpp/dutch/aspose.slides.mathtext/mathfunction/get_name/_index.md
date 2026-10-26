---
title: get_Name()
second_title: Aspose.Slides voor C++ API-referentie
description: Functienaam Bijvoorbeeld, functienamen zijn sin en cos
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() methode


Functienaam Bijvoorbeeld, functienamen zijn sin en cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathFunction](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)