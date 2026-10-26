---
title: get_VerticalJustification()
second_title: Справочник API Aspose.Slides для C++
description: "Вертикальное выравнивание группового символа. Задает выравнивание объекта относительно базовой линии. Например, когда групповой символ находится над объектом, VerticalJustification со значением Top указывает, что верхняя часть объекта располагается на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom."
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() метод


Вертикальное выравнивание группового символа. Указывает выравнивание объекта относительно базовой линии. Для примера, когда групповой символ находится над объектом, VerticalJustification со значением Top указывает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## Примечания


Пример: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Смотрите также

* Перечисление [MathTopBotPositions](../../mathtopbotpositions/)
* Класс [MathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)