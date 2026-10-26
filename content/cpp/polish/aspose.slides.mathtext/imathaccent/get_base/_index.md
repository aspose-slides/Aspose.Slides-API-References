---
title: get_Base()
second_title: Odwołanie API Aspose.Slides dla C++
description: Argument, do którego zastosowano akcent
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() metoda

Argument, do którego zastosowano akcent

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Uwagi

Przykład:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathAccent](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)