---
title: set_Differential()
second_title: Aspose.Slides för C++ API-referens
description: "Differential. När true, rutan fungerar som ett differential (t.ex., \\uD835\\uDC51\\uD835\\uDC65 i en integrand), och får lämplig horisontell avstånd för det matematiska differentialet. Standard: false"
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) method

Differential. När true, rutan fungerar som ett differential (t.ex., \\uD835\\uDC51\\uDC65 i en integrand), och får lämplig horisontell avstånd för det matematiska differentialet. Standard: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## Anmärkningar

Exempel: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Se också

* Klass [IMathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)