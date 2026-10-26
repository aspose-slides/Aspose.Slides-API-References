---
title: CreateMathFunction()
second_title: Aspose.Slides для C++ справочник API
description: Создает математическую функцию
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) метод


Создает математическую функцию

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, используемый в качестве имени функции |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, используемый в качестве аргумента функции |

### Возвращаемое значение

новая математическая функция

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) метод


Создает математическую функцию

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Имя функции |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, используемый в качестве аргумента функции |

### Возвращаемое значение

новая математическая функция

## См. также

* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathFunction](../../imathfunction/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathFunctionFactory](../)
* Класс [String](../../../system/string/)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)