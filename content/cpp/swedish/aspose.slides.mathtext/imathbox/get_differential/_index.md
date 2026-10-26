---
title: get_Differential()
second_title: Aspose.Slides för C++ API-referens
description: "Differential. När true, fungerar rutan som en differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 i ett integrand), och får det lämpliga horisontella avståndet för den matematiska differentialen. Standard: false"
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() metod


Differential. När true, fungerar rutan som en differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 i ett integrand), och får det lämpliga horisontella avståndet för den matematiska differentialen. Standard: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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

* Klass [IMathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)