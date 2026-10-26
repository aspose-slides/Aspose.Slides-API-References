---
title: set_BaseJustification()
second_title: Справочник API Aspose.Slides для C++
description: "Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center"
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/imathmatrix/set_basejustification/
---
## IMathMatrix::set_BaseJustification(MathVerticalAlignment) метод

Указывает вертикальное выравнивание относительно окружающего текста. Возможные значения: top, bottom и center. По умолчанию: Center

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_BaseJustification(MathVerticalAlignment value)=0
```

## Примечания

Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## См. также

* Перечисление [MathVerticalAlignment](../../mathverticalalignment/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)