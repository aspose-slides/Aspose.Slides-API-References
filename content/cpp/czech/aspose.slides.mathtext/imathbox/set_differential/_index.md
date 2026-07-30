---
title: set_Differential()
second_title: Aspose.Slides pro C++ referenční příručku API
description: "Diferenciál. Když je true, krabice funguje jako diferenciál (např., \\uD835\\uDC51\\uD835\\uDC65 v integrandu) a získá odpovídající horizontální mezeru pro matematický diferenciál. Výchozí: false"
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) metoda


Diferenciál. Když je true, krabice funguje jako diferenciál (např., \\uD835\\uDC51\\uDC65 v integrandu) a získá odpovídající horizontální mezeru pro matematický diferenciál. Výchozí: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
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

* Třída [IMathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)