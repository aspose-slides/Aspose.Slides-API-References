---
title: set_Differential()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: "Differential Gdy true, pudełko zachowuje się jako różniczka (np., \\uD835\\uDC51\\uD835\\uDC65 w całce), i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. Domyślnie: false"
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) metoda

Differential Gdy true, pudełko zachowuje się jak różniczka (np. \\uD835\\uDC51\\uDC65 w całce), i otrzymuje odpowiednie odstępy poziome dla matematycznej różniczki. Domyślnie: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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