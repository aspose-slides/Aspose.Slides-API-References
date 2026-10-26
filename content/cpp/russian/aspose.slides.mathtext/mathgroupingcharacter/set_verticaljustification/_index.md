---
title: set_VerticalJustification()
second_title: Aspose.Slides для C++ справка API
description: "Вертикальное выравнивание группового символа. Указывает выравнивание объекта относительно базовой линии. Например, когда групповой символ находится над объектом, VerticalJustification со значением Top означает, что верхняя часть объекта располагается на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom."
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) метод

Вертикальное выравнивание группового символа. Указывает выравнивание объекта относительно базовой линии. Например, когда групповой символ находится над объектом, VerticalJustification со значением Top указывает, что верхняя часть объекта располагается на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top и Top для Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Примечания


Пример: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## См. также

* Перечисление [MathTopBotPositions](../../mathtopbotpositions/)
* Класс [MathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)