---
title: set_Differential()
second_title: Справочник API Aspose.Slides для C++
description: "Differential Когда истинно, коробка работает как дифференциал (например, \\uD835\\uDC51\\uD835\\uDC65 в интегранде) и получает соответствующий горизонтальный интервал для математического дифференциала. По умолчанию: false"
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) метод

Differential Когда истинно, коробка ведет себя как дифференциал (например, \\uD835\\uDC51\\uD835\\uDC65 в интегранде), и получает соответствующий горизонтальный интервал для математического дифференциала. По умолчанию: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
```

## Примечания

Пример: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## См. также

* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)