---
title: get_BaseJustification()
second_title: Aspose.Slides для C++ API Reference
description: "Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center"
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() метод

Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## Примечания

Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Смотрите также

* Перечисление [MathVerticalAlignment](../../mathverticalalignment/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)