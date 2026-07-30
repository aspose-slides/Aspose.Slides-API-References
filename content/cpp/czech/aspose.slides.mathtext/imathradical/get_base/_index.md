---
title: get_Base()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Základní argument
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() metoda


Základní argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Poznámky


Příklad: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // krychlový kořen
auto baseElem = radical->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathRadical](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)