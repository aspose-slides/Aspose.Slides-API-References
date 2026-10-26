---
title: get_Base()
second_title: Aspose.Slides pro C++ API Reference
description: Základní argument
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() metoda


Základní argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Poznámky


Příklad: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathElement](../../imathelement/)
* třída [MathRadical](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)