---
title: get_Base()
second_title: Aspose.Slides dla C++ Referencja API
description: Argument Base
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() metoda

Argument Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathPhantom](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)