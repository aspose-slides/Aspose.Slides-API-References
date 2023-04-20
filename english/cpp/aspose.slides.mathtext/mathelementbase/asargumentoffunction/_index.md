---
title: AsArgumentOfFunction()
second_title: Aspose.Slides for C++ API Reference
description: Takes specified function using this instance as the argument
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) method


Takes specified function using this instance as the argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Function name |

### Return Value

New math element of type [IMathFunction](../../imathfunction/)
## Remarks



Example: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) method


Takes specified function using this instance as the argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
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

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) method


Takes specified function using this instance as the argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
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
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) method


Takes specified function using this instance as the argument and specified additional argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | One of the common function type of two arguments: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Additional argument depending on the type of function |

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

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) method


Takes specified function using this instance as the argument and specified additional argument

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
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
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)