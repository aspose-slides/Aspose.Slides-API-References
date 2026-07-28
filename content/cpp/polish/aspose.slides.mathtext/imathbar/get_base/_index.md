---
title: get_Base()
second_title: Aspose.Slides dla interfejsu API C++
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() metoda


Argument bazowy

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Uwagi


Przykład: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathBar](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)