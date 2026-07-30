---
title: get_Base()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Argument, na který byl akcent aplikován
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() metoda

Argument, na který byl akcent aplikován

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
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
* Třída [IMathAccent](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)