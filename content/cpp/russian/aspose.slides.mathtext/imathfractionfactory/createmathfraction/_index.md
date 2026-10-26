---
title: CreateMathFraction()
second_title: Справочник API Aspose.Slides для C++
description: Создает математическую дробь
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) метод


Создает математическую дробь

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Числитель |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Знаменатель |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Тип дроби |

### Возвращаемое значение

Новая математическая дробь [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) метод


Создает математическую дробь

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Числитель |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Знаменатель |

### Возвращаемое значение

Новая математическая дробь [IMathFraction](../../imathfraction/)

## См. также

* Перечисление [MathFractionTypes](../../mathfractiontypes/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathFraction](../../imathfraction/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathFractionFactory](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)