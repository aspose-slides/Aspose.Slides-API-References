---
title: get_Format()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vlastnosti formátování textu
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() metoda


Vlastnosti formátování textu

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## Poznámky


Příklad: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPortionFormat](../../../aspose.slides/iportionformat/)
* Třída [IMathematicalText](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)