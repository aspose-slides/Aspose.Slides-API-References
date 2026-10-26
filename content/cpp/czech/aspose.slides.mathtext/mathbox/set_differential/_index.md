---
title: set_Differential()
second_title: Aspose.Slides pro C++ API Reference
description: "Differential Když je true, krabice funguje jako diferenciál (např., \\uD835\\uDC51\\uD835\\uDC65 v integrandu), a získá vhodné vodorovné odsazení pro matematický diferenciál. Výchozí: false"
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) metoda

Differential Když je true, krabice funguje jako diferenciál (např., \\uD835\\uDC51\\uDC65 v integrandu) a získá vhodné vodorovné odsazení pro matematický diferenciál. Výchozí: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## Poznámky


Příklad: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Viz také

* Třída [MathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)