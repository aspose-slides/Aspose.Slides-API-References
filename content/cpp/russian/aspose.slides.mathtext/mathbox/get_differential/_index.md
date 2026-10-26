---
title: get_Differential()
second_title: Aspose.Slides для C++ справка по API
description: "Differential Когда true, коробка действует как дифференциал (например, \\uD835\\uDC51\\uD835\\uDC65 в интегранде) и получает соответствующий горизонтальный отступ для математического дифференциала. По умолчанию: false"
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() метод


Differential Когда true, коробка действует как дифференциал (например, \\uD835\\uDC51\\uD835\\uDC65 в интегранде) и получает соответствующий горизонтальный отступ для математического дифференциала. По умолчанию: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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

* Класс [MathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)