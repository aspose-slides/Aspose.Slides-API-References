---
title: AsArgumentOfFunction()
second_title: Aspose.Slides для C++: справка API
description: Принимает указанную функцию, используя данный экземпляр в качестве аргумента
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) метод

Принимает указанную функцию, используя данный экземпляр в качестве аргумента

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Имя функции |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)

## Примечания



Пример: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) метод

Принимает указанную функцию, используя данный экземпляр в качестве аргумента

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Имя функции |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)

## Примечания



Пример: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) метод

Принимает указанную функцию, используя данный экземпляр в качестве аргумента

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Одна из распространённых функций с одним аргументом |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)

## Примечания



Пример: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) метод

Принимает указанную функцию, используя данный экземпляр в качестве аргумента, и указанный дополнительный аргумент

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Одна из распространённых функций с двумя аргументами: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Дополнительный аргумент, зависящий от типа функции |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)

## Примечания



Пример: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Возвращает логарифм 'x' по основанию '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) метод

Принимает указанную функцию, используя данный экземпляр в качестве аргумента, и указанный дополнительный аргумент

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Одна из распространённых функций с двумя аргументами: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Дополнительный аргумент, зависящий от типа функции |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)

## Примечания



Пример: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Возвращает логарифм 'x' по основанию '5'
```

## См. также

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)