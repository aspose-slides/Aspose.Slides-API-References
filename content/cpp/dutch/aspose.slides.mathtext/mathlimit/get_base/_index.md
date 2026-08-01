---
title: get_Base()
second_title: Aspose.Slides voor C++ API-referentie
description: Base-argument
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() methode


Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathLimit](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)