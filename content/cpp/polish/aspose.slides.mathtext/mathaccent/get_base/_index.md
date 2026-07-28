---
title: get_Base()
second_title: Aspose.Slides dla C++ API Odniesienie
description: Argument, do którego zastosowano akcent
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() metoda

Argument, do którego zastosowano akcent

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
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
* Klasa [MathAccent](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)