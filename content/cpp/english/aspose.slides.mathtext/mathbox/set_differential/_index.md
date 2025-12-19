---
title: set_Differential()
second_title: Aspose.Slides for C++ API Reference
description: "Differential When true, the box acts as a differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false"
type: docs
weight: 79
url: /aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) method


Differential When true, the box acts as a differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## Remarks


Example: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## See Also

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)