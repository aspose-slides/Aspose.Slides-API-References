---
title: get_Base()
second_title: Referencja API Aspose.Slides dla C++
description: Argument funkcji
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() metoda

Argument funkcji

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Uwagi

Przykład: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathFunction](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)