---
title: get_Base()
second_title: Aspose.Slides dla C++ - Referencja API
description: Argument bazowy
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() metoda


Argument bazowy

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Uwagi


Przykład: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)