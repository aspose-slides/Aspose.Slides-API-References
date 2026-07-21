---
title: get_BaseJustification()
second_title: Aspose.Slides для справочника API C++
description: "Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom, center. По умолчанию: Center"
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() метод

Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## Замечания


Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## См. также

* Перечисление [MathVerticalAlignment](../../mathverticalalignment/)
* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)