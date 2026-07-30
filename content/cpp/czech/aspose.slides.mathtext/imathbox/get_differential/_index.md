---
title: get_Differential()
second_title: Aspose.Slides pro C++ referenční příručka API
description: "Differential. Když je true, box se chová jako diferenciál (např. \\uD835\\uDC51\\uD835\\uDC65 v integrandu) a získává odpovídající vodorovné rozestupy pro matematický diferenciál. Default: false"
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() metoda


Differential. Když je true, box se chová jako diferenciál (např. \\uD835\\uDC51\\uDC65 v integrandu) a získává odpovídající vodorovné rozestupy pro matematický diferenciál. Default: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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