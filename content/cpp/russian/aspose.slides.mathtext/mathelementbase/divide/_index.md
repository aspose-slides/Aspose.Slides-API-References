---
title: Divide()
second_title: Справочник API Aspose.Slides для C++
description: Создает дробь с этим числителем и указанным знаменателем
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) метод

Создает дробь с этим числителем и указанным знаменателем

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Знаменатель |

### Возвращаемое значение

новая дробь
## Примечания

Пример: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) метод

Создает дробь с этим числителем и указанным знаменателем

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Знаменатель |

### Возвращаемое значение

новая дробь
## Примечания

Пример: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) метод

Создает дробь указанного типа с этим числителем и указанным знаменателем

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Знаменатель |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Тип дроби: Bar, NoBar, Skewed, Linear |

### Возвращаемое значение

новая дробь
## Примечания

Пример: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) метод

Создает дробь указанного типа с этим числителем и указанным знаменателем

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | Знаменатель |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | Тип дроби: Bar, NoBar, Skewed, Linear |

### Возвращаемое значение

новая дробь
## Примечания

Пример: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## См. также

* Перечисление [MathFractionTypes](../../mathfractiontypes/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathFraction](../../imathfraction/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)