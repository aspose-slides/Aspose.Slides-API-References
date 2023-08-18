---
title: get_Differential()
second_title: Aspose.Slides for C++ API Reference
description: "Differential When true, the box acts as a differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false"
type: docs
weight: 66
url: /aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() method


Differential When true, the box acts as a differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
```

## Remarks


Example: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(Aspose::Slides::MathText::MathIntegralTypes::Simple, u"0", u"1");
```

## See Also

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)