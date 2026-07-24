---
title: get_Differential()
second_title: Aspose.Slides für C++ API-Referenz
description: "Differential Wenn true, verhält sich die Box wie ein Differential (z. B. \\uD835\\uDC51\\uD835\\uDC65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false"
type: docs
weight: 66
url: /de/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() Methode


Differential Wenn true, verhält sich die Box wie ein Differential (z. B. \\uD835\\uDC51\\uDC65 in einem Integranden) und erhält den entsprechenden horizontalen Abstand für das mathematische Differential. Standard: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## Remarks


Beispiel: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## See Also

* Klasse [MathBox](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)