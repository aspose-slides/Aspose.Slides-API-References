---
title: get_Base()
second_title: Aspose.Slides för C++ API-referens
description: Base argument
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() metod


Base-argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## Anmärkningar


Exempel: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathLimit](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)