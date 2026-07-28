---
title: get_LimitLocation()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Położenie limitów (indeks dolny i indeks górny)
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() metoda

Położenie limitów (indeks dolny i indeks górny)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Uwagi


Przykład: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Zobacz także

* Wyliczenie [MathLimitLocations](../../mathlimitlocations/)
* Klasa [IMathNaryOperatorProperties](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)