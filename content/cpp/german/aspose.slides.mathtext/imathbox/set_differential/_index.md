---
title: set_Differential()
second_title: Aspose.Slides für C++ API-Referenz
description: "Differential. Wenn true, wirkt die Box als Differential (z. B., \\uD835\\uDC51\\uD835\\uDC65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false"
type: docs
weight: 79
url: /de/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) Methode


Differential. Wenn true, wirkt die Box als Differential (z. B. \\uD835\\uDC51\\uDC65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## Bemerkungen


Beispiel: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Siehe auch

* Klasse [IMathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)