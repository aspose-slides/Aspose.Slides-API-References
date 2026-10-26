---
title: CreateMathLimit()
second_title: Справочник API Aspose.Slides для C++
description: Создает IMathLimit
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) метод

Создает [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый аргумент для применения предела |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент предела |
| upperLimit | **bool** | Устанавливает расположение предела сверху |

### Возвращаемое значение

новый математический предел

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) метод

Создает [IMathLimit](../../imathlimit/) с пределом внизу

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый аргумент для применения предела |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент предела |

### Возвращаемое значение

новый математический предел

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathLimit](../../imathlimit/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathLimitFactory](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)