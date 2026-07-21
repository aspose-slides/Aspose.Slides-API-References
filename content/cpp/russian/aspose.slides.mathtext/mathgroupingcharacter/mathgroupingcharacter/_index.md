---
title: MathGroupingCharacter()
second_title: Aspose.Slides для C++ справочник API
description: Инициализирует новый экземпляр класса MathGroupingCharacter с символом группировки по умолчанию U+23DF (BOTTOM CURLY BRACKET)
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) конструктор

Инициализирует новый экземпляр класса [MathGroupingCharacter](../) с символом группировки по умолчанию U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый элемент, к которому применяется штрих |
## Примечания



Пример:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) конструктор

Инициализирует новый экземпляр класса [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый элемент, к которому применяется штрих |
| character | char16_t | Символ группировки |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Положение символа группировки |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Вертикальное выравнивание символа группировки |
## Примечания



Пример:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## См. также

* Перечисление [MathTopBotPositions](../../mathtopbotpositions/)
* Определение типа [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)