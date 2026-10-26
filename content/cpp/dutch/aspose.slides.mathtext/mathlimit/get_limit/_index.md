---
title: get_Limit()
second_title: Aspose.Slides voor C++ API-referentie
description: Limietargument
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() methode


Limietargument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Opmerkingen


Voorbeeld: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)