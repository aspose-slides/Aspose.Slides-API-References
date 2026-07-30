---
title: get_Base()
second_title: Aspose.Slides pro C++ API Reference
description: Argument Base
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() metoda


Argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
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
* Třída [MathLimit](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)