---
title: get_Differential()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: "Różniczka. Gdy true, pole zachowuje się jako różniczka (np., \\uD835\\uDC51\\uD835\\uDC65 w całce), i otrzymuje odpowiednie odstępy poziome dla różniczki matematycznej. Domyślnie: false"
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() metoda

Differential. Gdy true, pole zachowuje się jako różniczka (np., \\uD835\\uDC51\\uDC65 w całce), i otrzymuje odpowiednie odstępy poziome dla różniczki matematycznej. Domyślnie: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
```

## Uwagi


Przykład:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Zobacz także

* Klasa [IMathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)