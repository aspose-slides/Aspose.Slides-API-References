---
title: get_Format()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vlastnosti formátování textu
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathematicaltext/get_format/
---
## MathematicalText::get_Format() metoda


Vlastnosti formátování textu

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::MathematicalText::get_Format() override
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
* Třída [MathematicalText](../)
* Prostor názvů [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)