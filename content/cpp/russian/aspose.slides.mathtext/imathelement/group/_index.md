---
title: Group()
second_title: Aspose.Slides для C++ справочник API
description: Размещает этот элемент в группе, используя нижнюю фигурную скобку
type: docs
weight: 248
url: /ru/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() метод


Размещает этот элемент в группе, используя нижнюю фигурную скобку

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Возвращаемое значение

Новый экземпляр типа [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Примечания



Пример: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) метод


Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или другой

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Символ группировки, такой как нижняя фигурная скобка (U+23DF) или любой другой |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Позиция символа группировки |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Вертикальное выравнивание символа группы. Указывает выравнивание объекта относительно базовой линии. Например, когда символ группы находится над объектом, VerticalJustification со значением Top означает, что верхняя часть объекта находится на базовой линии; когда VerticalJustification установлен в Bottom, нижняя часть объекта находится на базовой линии |

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
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)