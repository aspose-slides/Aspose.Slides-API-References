---
title: CreateMathBar()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт математическую черту, применяя к элементу
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathbarfactory/createmathbar/
---
## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) метод

Создает математическую черту, применяя к элементу

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply bar |

### Возвращаемое значение

новый элемент математической черты

## IMathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) метод

Создает математическую черту, применяя к элементу

```cpp
virtual System::SharedPtr<IMathBar> Aspose::Slides::MathText::IMathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Math element to apply bar |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position of the bar |

### Возвращаемое значение

новый элемент математической черты

## См. также

* Перечисление [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBar](../../imathbar/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathBarFactory](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)