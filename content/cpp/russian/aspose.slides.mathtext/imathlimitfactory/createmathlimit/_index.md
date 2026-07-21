---
title: CreateMathLimit()
second_title: Aspose.Slides для C++ API Справка
description: Создаёт IMathLimit
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) метод


Создаёт [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый аргумент для применения предела |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент предела |
| upperLimit | **bool** | Устанавливает расположение предела сверху |

### Возвращаемое значение

новый математический предел

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) метод


Создаёт [IMathLimit](../../imathlimit/) с предельным элементом внизу

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый аргумент для применения предела |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент предела |

### Возвращаемое значение

новый математический предел

## См. также

* Типоопределение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathLimit](../../imathlimit/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathLimitFactory](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)