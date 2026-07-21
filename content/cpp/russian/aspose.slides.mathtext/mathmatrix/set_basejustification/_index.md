---
title: set_BaseJustification()
second_title: Справка по API Aspose.Slides для C++
description: "Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center"
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) метод


Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## Примечания


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