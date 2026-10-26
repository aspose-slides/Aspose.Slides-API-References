---
title: set_LimitLocation()
second_title: Aspose.Slides dla C++ API Referencja
description: Lokalizacja limitów (indeks dolny i indeks górny)
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) metoda

Lokalizacja limitów (indeks dolny i indeks górny)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Uwagi

Przykład:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Zobacz także

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Klasa [IMathNaryOperatorProperties](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)