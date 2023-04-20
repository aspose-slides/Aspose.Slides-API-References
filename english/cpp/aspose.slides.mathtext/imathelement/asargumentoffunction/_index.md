---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API Reference
description: Takes specified function using this instance as the argument
type: docs
weight: 66
url: /cpp/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) method


Takes specified function using this instance as the argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Function name |

### Return Value

New math element of type [IMathFunction](../../imathfunction/)
## Remarks



Example: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) method


Takes specified function using this instance as the argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Function name |

### Return Value

New math element of type [IMathFunction](../../imathfunction/)
## Remarks



Example: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) method


Takes specified function using this instance as the argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | One of the common function type of one argument |

### Return Value

New math element of type [IMathFunction](../../imathfunction/)
## Remarks



Example: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(Aspose::Slides::MathText::MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) method


Takes specified function using this instance as the argument and specified additional argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Additional argument depending on the type of function |

### Return Value

New math element of type [IMathFunction](../../imathfunction/)
## Remarks



Example: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(Aspose::Slides::MathText::MathFunctionsOfTwoArguments::Log, logarithmBase);
// Returns the logarithm of 'x' to the base '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) method


Takes specified function using this instance as the argument and specified additional argument

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Additional argument depending on the type of function |

### Return Value

New math element of type [IMathFunction](../../imathfunction/)
## Remarks



Example: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(Aspose::Slides::MathText::MathFunctionsOfTwoArguments::Log, u"5");
// Returns the logarithm of 'x' to the base '5'
```

## See Also

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)