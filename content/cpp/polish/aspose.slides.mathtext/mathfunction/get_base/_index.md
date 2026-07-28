---
title: get_Base()
second_title: Aspose.Slides dla C++ referencja API
description: Argument funkcji
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() metoda


Argument funkcji

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Uwagi


Przykład: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathFunction](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)