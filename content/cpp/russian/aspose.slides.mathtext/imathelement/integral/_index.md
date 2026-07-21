---
title: Integral()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет интегрирование
type: docs
weight: 196
url: /ru/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) метод


Выполняет интегрирование

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Тип интеграла |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Нижний предел интеграла |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Верхний предел интеграла |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | расположение пределов |

### Возвращаемое значение

Новый экземпляр типа [IMathNaryOperator](../../imathnaryoperator/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) метод


Выполняет интегрирование

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Тип интеграла |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Нижний предел интеграла |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Верхний предел интеграла |

### Возвращаемое значение

Новый экземпляр типа [IMathNaryOperator](../../imathnaryoperator/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) метод


Выполняет интегрирование без пределов

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Тип интеграла |

### Возвращаемое значение

Новый экземпляр типа [IMathNaryOperator](../../imathnaryoperator/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) метод


Выполняет интегрирование

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Тип интеграла |
| lowerLimit | [System::String](../../../system/string/) | Нижний предел интеграла |
| upperLimit | [System::String](../../../system/string/) | Верхний предел интеграла |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | расположение пределов |

### Возвращаемое значение

Новый экземпляр типа [IMathNaryOperator](../../imathnaryoperator/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) метод


Выполняет интегрирование

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | Тип интеграла |
| lowerLimit | [System::String](../../../system/string/) | Нижний предел интеграла |
| upperLimit | [System::String](../../../system/string/) | Верхний предел интеграла |

### Возвращаемое значение

Новый экземпляр типа [IMathNaryOperator](../../imathnaryoperator/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## См. также

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathNaryOperator](../../imathnaryoperator/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)