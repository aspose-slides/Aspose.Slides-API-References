---
title: get_Base()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Základní argument
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() metoda


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Poznámky


Příklad: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathBorderBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)