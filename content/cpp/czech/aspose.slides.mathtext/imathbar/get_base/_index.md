---
title: get_Base()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Základní argument
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() metoda


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Poznámky


Příklad: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathElement](../../imathelement/)
* třída [IMathBar](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)