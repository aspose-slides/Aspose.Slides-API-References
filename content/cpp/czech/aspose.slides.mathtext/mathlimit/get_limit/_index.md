---
title: get_Limit()
second_title: Aspose.Slides pro C++ – reference API
description: Argument limitu
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() metoda


Argument limitu

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
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
* Třída [MathLimit](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)