---
title: get_Limit()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Argument limitu
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() metoda


Argument limitu

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Poznámky


Příklad:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathLimit](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)