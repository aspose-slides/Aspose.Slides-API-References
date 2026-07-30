---
title: get_Base()
second_title: Aspose.Slides pro C++ API referenci
description: Argument, ke kterému byl akcent aplikován
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() metoda


Argument, ke kterému byl akcent aplikován

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Poznámky


Příklad: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathAccent](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)