---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides для C++ Справочник API
description: Создает математический группирующий символ
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) method


Создает математический группирующий символ

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется группирующий символ |
| character | char16_t | группирующий символ |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | позиция группирующего символа |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | вертикальное выравнивание |

### Возвращаемое значение

новый элемент группирующего символа

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) method


Создает математический группирующий символ

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется группирующий символ |

### Возвращаемое значение

новый элемент группирующего символа

## См. также

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)