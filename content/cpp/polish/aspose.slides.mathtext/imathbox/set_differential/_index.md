---
title: set_Differential()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Różniczka. Gdy true, pole zachowuje się jak różniczka (np., \\uD835\\uDC51\\uD835\\uDC65 w całce), i otrzymuje odpowiednie poziome odstępy dla matematycznej różniczki. Domyślnie: false"
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) method

Różniczka. Gdy true, pole zachowuje się jak różniczka (np., \\uD835\\uDC51\\uDC65 w całce), i otrzymuje odpowiednie poziome odstępy dla matematycznej różniczki. Domyślnie: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
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