---
title: get_LimitLocation()
second_title: Aspose.Slides dla C++ Referencja API
description: Lokalizacja limitów (indeks dolny i indeks górny)
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() metoda


Lokalizacja limitów (indeks dolny i indeks górny)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Uwagi


Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Zobacz także

* Wyliczenie [MathLimitLocations](../../mathlimitlocations/)
* Klasa [MathNaryOperator](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)