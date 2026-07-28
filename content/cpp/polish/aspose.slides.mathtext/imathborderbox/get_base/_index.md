---
title: get_Base()
second_title: Aspose.Slides for C++ – Dokumentacja API
description: argument Base
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() metoda


argument Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Uwagi


Przykład:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathBorderBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)