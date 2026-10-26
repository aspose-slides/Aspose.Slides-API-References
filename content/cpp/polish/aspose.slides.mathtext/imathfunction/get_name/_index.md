---
title: get_Name()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Nazwa funkcji Na przykład nazwy funkcji to sin i cos
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() metoda

Nazwa funkcji Na przykład nazwy funkcji to sin i cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Uwagi

Przykład:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathFunction](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)