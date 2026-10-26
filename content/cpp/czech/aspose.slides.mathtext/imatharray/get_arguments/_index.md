---
title: get_Arguments()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Množina položek pole
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() metoda


Množina položek pole

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
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
* Třída [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)