---
title: get_Differential()
second_title: Aspose.Slides для C++ API Справка
description: "Дифференциал. Когда истинно, поле действует как дифференциал (например, \\uD835\\uDC51\\uD835\\uDC65 в подынтеграле), и получает соответствующее горизонтальное расстояние для математического дифференциала. По умолчанию: false"
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() метод


Дифференциал. Когда истинно, поле действует как дифференциал (например, \\uD835\\uDC51\\uDC65 в подынтеграле), и получает соответствующее горизонтальное расстояние для математического дифференциала. По умолчанию: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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

* Класс [IMathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)