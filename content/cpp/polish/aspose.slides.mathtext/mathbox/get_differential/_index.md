---
title: get_Differential()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Differential Gdy true, pudełko zachowuje się jak różniczka (e.g., \\uD835\\uDC51\\uD835\\uDC65 w wyrażeniu podcałkowym), i otrzymuje odpowiednie poziome odstępy dla różniczki matematycznej. Domyślnie: false"
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() metoda


Differential Gdy true, pudełko zachowuje się jak różniczka (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), i otrzymuje odpowiednie poziome odstępy dla różniczki matematycznej. Domyślnie: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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

* Klasa [MathBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)