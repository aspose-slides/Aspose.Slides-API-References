---
title: get_Base()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Základní argument
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() metoda


Base argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Poznámky


Příklad: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)