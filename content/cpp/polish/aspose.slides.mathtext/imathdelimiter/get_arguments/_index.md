---
title: get_Arguments()
second_title: Aspose.Slides dla C++ - Referencja API
description: Jedno lub więcej elementów matematycznych oddzielonych znakami separatora
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() metoda


Jedno lub więcej elementów matematycznych oddzielonych znakami separatora

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Uwagi


Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElementCollection](../../imathelementcollection/)
* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)