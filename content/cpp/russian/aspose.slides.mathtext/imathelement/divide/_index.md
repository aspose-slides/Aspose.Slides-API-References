---
title: Divide()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт дробь с этим числителем и указанным знаменателем
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) метод

Создаёт дробь с этим числителем и указанным знаменателем

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Знаменатель |

### Возвращаемое значение

новая дробь
## Примечания



Пример: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) метод

Создаёт дробь с этим числителем и указанным знаменателем

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
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
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) метод

Создаёт дробь указанного типа с этим числителем и указанным знаменателем

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Знаменатель |
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

## IMathElement::Divide(System::String, MathFractionTypes) метод

Создаёт дробь указанного типа с этим числителем и указанным знаменателем

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
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
* Тип определённый [SharedPtr](../../../system/sharedptr/)
* Класс [IMathFraction](../../imathfraction/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)