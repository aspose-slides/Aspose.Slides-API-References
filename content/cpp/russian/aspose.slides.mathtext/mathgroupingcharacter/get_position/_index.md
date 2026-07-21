---
title: get_Position()
second_title: Справочник API Aspose.Slides для C++
description: "Позиция символа группировки. По умолчанию: Bottom"
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathgroupingcharacter/get_position/
---
## MathGroupingCharacter::get_Position() метод


Позиция символа группировки. По умолчанию: Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_Position() override
```

## Примечания


Пример: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## См. также

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Класс [MathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)