---
title: get_Position()
second_title: Справка API Aspose.Slides для C++
description: "Позиция линии шкалы. По умолчанию: Верх"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathbar/get_position/
---
## IMathBar::get_Position() метод

Позиция линии шкалы. По умолчанию: Верх

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathBar::get_Position()=0
```

## Примечания

Пример:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
mathBar->set_Position(MathTopBotPositions::Bottom);
```

## См. также

* Перечисление [MathTopBotPositions](../../mathtopbotpositions/)
* Класс [IMathBar](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)