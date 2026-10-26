---
title: get_VerticalJustification()
second_title: Aspose.Slides для C++ справочник API
description: "Вертикальное выравнивание группового символа. Задает выравнивание объекта относительно базовой линии. Например, когда групповой символ находится над объектом, VerticalJustification со значением Top указывает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top, и Top для Position=Bottom"
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() метод

Вертикальное выравнивание группового символа. Задает выравнивание объекта относительно базовой линии. Например, когда групповой символ находится над объектом, VerticalJustification со значением Top указывает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## Примечания


Пример: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Смотрите также

* Перечисление [MathTopBotPositions](../../mathtopbotpositions/)
* Класс [IMathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)