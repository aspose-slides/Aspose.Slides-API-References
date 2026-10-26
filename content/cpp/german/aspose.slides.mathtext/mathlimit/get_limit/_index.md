---
title: get_Limit()
second_title: Aspose.Slides für C++ API-Referenz
description: Limit-Argument
type: docs
weight: 14
url: /de/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() Methode


Limit-Argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
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
* Klasse [MathLimit](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)