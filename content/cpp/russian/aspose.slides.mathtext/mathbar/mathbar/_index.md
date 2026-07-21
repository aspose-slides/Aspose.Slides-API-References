---
title: MathBar()
second_title: Aspose.Slides для C++ справочник API
description: Инициализирует MathBar с надчеркой (позиция сверху)
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) конструктор


Инициализирует [MathBar](../) с надчеркой (позиция сверху)

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый элемент, к которому применяется черта |
## Замечания



Пример: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) конструктор


Инициализирует [MathBar](../) с указанной позицией

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый элемент, к которому применяется черта |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Позиция линии черты. |
## Замечания



Пример: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## См. также

* Перечисление [MathTopBotPositions](../../mathtopbotpositions/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBar](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)