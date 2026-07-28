---
title: get_Base()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() metoda


Argument bazowy

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## Uwagi


Przykład: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBorderBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)