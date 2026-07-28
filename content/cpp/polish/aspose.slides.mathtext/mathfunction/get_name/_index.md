---
title: get_Name()
second_title: Aspose.Slides – referencja API dla C++
description: Nazwa funkcji. Na przykład nazwy funkcji to sin i cos
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() metoda


Nazwa funkcji Na przykład, nazwy funkcji to sin i cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
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
* Klasa [MathFunction](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)