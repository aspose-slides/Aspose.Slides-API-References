---
title: get_Arguments()
second_title: Aspose.Slides pro C++ API Reference
description: Jeden nebo více matematických prvků oddělených znaky oddělovače
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() metoda

Jeden nebo více matematických prvků oddělených znakem oddělovače

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Poznámky

Příklad: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElementCollection](../../imathelementcollection/)
* Třída [IMathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)