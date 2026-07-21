---
title: Group()
second_title: Aspose.Slides для C++ справочник API
description: Размещает этот элемент в группе, используя нижнюю фигурную скобку
type: docs
weight: 235
url: /ru/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() метод


Размещает этот элемент в группе, используя нижнюю фигурную скобку

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Возвращаемое значение

Новый экземпляр типа [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Примечания



Пример: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) метод


Размещает этот элемент в группе, используя группирующий символ, такой как нижняя фигурная скобка или другой

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| character | char16_t | Группирующий символ, такой как BOTTOM CURLY BRACKET (U+23DF) или любой другой |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Позиция группирующего символа |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Вертикальное выравнивание группирующего символа. Задает выравнивание объекта относительно базовой линии. Например, когда группирующий символ находится над объектом, VerticalJustification со значением Top указывает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии |

### Возвращаемое значение

Новый экземпляр типа [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Примечания



Пример: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## См. также

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)