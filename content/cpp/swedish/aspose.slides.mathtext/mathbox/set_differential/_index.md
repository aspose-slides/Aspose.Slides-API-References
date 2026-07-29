---
title: set_Differential()
second_title: Aspose.Slides för C++ API-referens
description: "Differential När true, lådan fungerar som ett differential (t.ex., \\uD835\\uDC51\\uD835\\uDC65 i ett integrand), och får lämplig horisontell avstånd för den matematiska differentialen. Default: false"
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) metod


Differential När true, lådan fungerar som ett differential (e.g., \\uD835\\uDC51\\uDC65 i ett integrand), och får lämplig horisontell avstånd för den matematiska differentialen. Default: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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