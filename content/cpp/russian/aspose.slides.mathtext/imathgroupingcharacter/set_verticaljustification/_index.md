---
title: set_VerticalJustification()
second_title: Aspose.Slides для C++ справочник API
description: "Вертикальное выравнивание группирующего символа. Задает выравнивание объекта относительно базовой линии. Например, когда группирующий символ находится над объектом, VerticalJustification of Top означает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top, и Top для Position=Bottom"
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) method


Вертикальное выравнивание группирующего символа. Задает выравнивание объекта относительно базовой линии. Например, когда группирующий символ находится над объектом, VerticalJustification of Top означает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии. По умолчанию: Bottom для Position=Top, и Top для Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Примечание


Пример: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## См. также

* Перечисление [MathTopBotPositions](../../mathtopbotpositions/)
* Класс [IMathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)