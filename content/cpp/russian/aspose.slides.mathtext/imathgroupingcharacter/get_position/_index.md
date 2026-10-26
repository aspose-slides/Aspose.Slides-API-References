---
title: get_Position()
second_title: Справочник API Aspose.Slides для C++
description: "Позиция символа группировки. По умолчанию: Bottom"
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathgroupingcharacter/get_position/
---
## IMathGroupingCharacter::get_Position() метод


Позиция символа группировки. По умолчанию: Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_Position()=0
```

## Примечания


Пример: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Position(MathTopBotPositions::Top);
```

## Смотрите также

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Класс [IMathGroupingCharacter](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)