---
title: get_Base()
second_title: Aspose.Slides pro C++ – reference API
description: Základní argument
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() metoda


Základní argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## Poznámky


Příklad: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathLimit](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)