---
title: get_Base()
second_title: Aspose.Slides für C++ API-Referenz
description: Basisargument
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() Methode


Base Argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## Bemerkungen


Beispiel: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathLimit](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)