---
title: set_Differential()
second_title: Справочник API Aspose.Slides для C++
description: "Дифференциал. Когда true, элемент действует как дифференциал (например, \\uD835\\uDC51\\uD835\\uDC65 в интегранде) и получает соответствующий горизонтальный интервал для математического дифференциала. По умолчанию: false"
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) метод


Дифференциал. Если true, элемент ведёт себя как дифференциал (например, \\uD835\\uDC51\\uDC65 в интегранде) и получает соответствующий горизонтальный интервал для математического дифференциала. По умолчанию: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## Примечания


Пример:
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## Смотрите также

* Класс [IMathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)