---
title: get_Base()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() metoda

Base argument

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
```

## Uwagi

Przykład: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBar](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)