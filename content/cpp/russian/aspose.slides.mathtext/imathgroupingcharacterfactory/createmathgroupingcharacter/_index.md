---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides для C++ справочник API
description: Создает символ группировки математики
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) метод

Создает символ группировки математики

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется символ группировки |
| character | char16_t | символ группировки |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | позиция символа группировки |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | вертикальное выравнивание |

### Возвращаемое значение

новый элемент символа группировки

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) метод

Создает символ группировки математики

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется символ группировки |

### Возвращаемое значение

новый элемент символа группировки

## См. также

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathGroupingCharacterFactory](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)