---
title: get_Arguments()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Jedno nebo více matematických prvků oddělených znakem oddělovače
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() metoda

Jedno nebo více matematických prvků oddělených znakem oddělovače

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
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
* Třída [MathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)