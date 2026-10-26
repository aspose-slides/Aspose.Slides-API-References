---
title: get_Base()
second_title: Aspose.Slides pro C++ referenční API
description: Argument funkce
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() metoda


Argument funkce

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
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
* Třída [MathFunction](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)