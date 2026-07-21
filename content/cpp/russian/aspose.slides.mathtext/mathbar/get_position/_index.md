---
title: get_Position()
second_title: Aspose.Slides для C++ справочник API
description: "Позиция линии полосы. По умолчанию: Top"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathbar/get_position/
---
## MathBar::get_Position() метод


Позиция линии полосы. Default: Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathBar::get_Position() override
```

## Примечания


Пример: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## См. также

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Класс [MathBar](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)