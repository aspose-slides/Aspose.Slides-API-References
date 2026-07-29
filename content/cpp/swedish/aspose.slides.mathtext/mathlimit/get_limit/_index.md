---
title: get_Limit()
second_title: Aspose.Slides för C++ API-referens
description: Gränsvärdesargument
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() metod

Gränsvärdesargument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Anmärkningar

Exempel:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathLimit](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)