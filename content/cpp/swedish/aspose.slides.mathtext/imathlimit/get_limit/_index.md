---
title: get_Limit()
second_title: Aspose.Slides för C++ API-referens
description: Gränsvärdesargument
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() metod


Gränsvärdesargument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Anmärkningar


Exempel: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Se även

* Typdef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathLimit](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)