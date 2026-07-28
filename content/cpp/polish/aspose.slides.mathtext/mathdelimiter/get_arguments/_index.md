---
title: get_Arguments()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Jeden lub więcej elementów matematycznych oddzielonych znakami delimitera
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() method


Jeden lub więcej elementów matematycznych oddzielonych znakami delimitera

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Uwagi


Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElementCollection](../../imathelementcollection/)
* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)