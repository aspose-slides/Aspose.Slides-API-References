---
title: get_Base()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Argument funkce
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() metoda


Argument funkce

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Poznámky


Příklad: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathFunction](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)