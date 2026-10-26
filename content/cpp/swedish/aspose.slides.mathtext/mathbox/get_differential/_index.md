---
title: get_Differential()
second_title: Aspose.Slides för C++ API-referens
description: "Differential När true, rutan fungerar som en differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 i ett integrand), och får lämplig horisontell avstånd för den matematiska differentialen. Standard: false"
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() metod


Differential När true, rutan fungerar som en differential (e.g., \\uD835\\uDC51\\uDC65 i ett integrand), och får lämplig horisontell avstånd för den matematiska differentialen. Standard: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## Anmärkningar


Exempel:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Se även

* Klass [MathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)