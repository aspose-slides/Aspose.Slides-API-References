---
title: get_Arguments()
second_title: Aspose.Slides pro C++ API Reference
description: Množina položek pole
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() metoda


Množina položek pole

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Poznámky


Příklad: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElementCollection](../../imathelementcollection/)
* Třída [MathArray](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)