---
title: AsArgumentOfFunction()
second_title: Aspose.Slides для C++ справочника API
description: Принимает указанную функцию, используя данный экземпляр в качестве аргумента
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) метод


Принимает указанную функцию, используя данный экземпляр в качестве аргумента

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Function name |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)
## Замечания



Пример: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) метод


Принимает указанную функцию, используя данный экземпляр в качестве аргумента

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Function name |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)
## Замечания



Пример: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) метод


Принимает указанную функцию, используя данный экземпляр в качестве аргумента

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | One of the common function type of one argument |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)
## Замечания



Пример: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) метод


Принимает указанную функцию, используя данный экземпляр в качестве аргумента и указанный дополнительный аргумент

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Additional argument depending on the type of function |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)
## Замечания



Пример: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Возвращает логарифм 'x' по основанию '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) метод


Принимает указанную функцию, используя данный экземпляр в качестве аргумента и указанный дополнительный аргумент

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Additional argument depending on the type of function |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)
## Замечания



Пример: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Возвращает логарифм 'x' по основанию '5'
```

## См. также

* Перечисление [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Перечисление [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Типоопределение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathFunction](../../imathfunction/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)