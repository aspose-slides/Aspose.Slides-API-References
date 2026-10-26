---
title: get_Base()
second_title: Aspose.Slides dla C++ Referencja API
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() metoda


Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Uwagi


Przykład: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathRadical](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)