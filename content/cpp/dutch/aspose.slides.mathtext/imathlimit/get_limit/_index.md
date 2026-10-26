---
title: get_Limit()
second_title: Aspose.Slides voor C++ API-referentie
description: Limietargument
type: docs
weight: 14
url: /nl/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() methode


Limietargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
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
* Klasse [IMathLimit](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)