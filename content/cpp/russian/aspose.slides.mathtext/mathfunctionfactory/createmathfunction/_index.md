---
title: CreateMathFunction()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт математическую функцию
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) метод

Создаёт математическую функцию

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, используемый как имя функции |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, используемый как аргумент функции |

### Возвращаемое значение

новая математическая функция

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) метод

Создаёт математическую функцию

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Имя функции |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, используемый как аргумент функции |

### Возвращаемое значение

новая математическая функция

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathFunction](../../imathfunction/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathFunctionFactory](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)