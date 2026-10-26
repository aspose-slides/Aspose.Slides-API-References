---
title: get_Base()
second_title: Aspose.Slides dla C++ – odniesienie API
description: argument Base
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() metoda


argument Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
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
* Klasa [IMathPhantom](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)