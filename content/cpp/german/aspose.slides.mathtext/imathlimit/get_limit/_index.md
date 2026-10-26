---
title: get_Limit()
second_title: Aspose.Slides für C++ API-Referenz
description: Limit-Argument
type: docs
weight: 14
url: /de/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() Methode


Limit-Argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Hinweise


Beispiel: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathLimit](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)