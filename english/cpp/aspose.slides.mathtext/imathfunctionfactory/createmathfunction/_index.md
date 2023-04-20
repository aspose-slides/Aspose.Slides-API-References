---
title: CreateMathFunction()
second_title: Aspose.Slides for C++ API Reference
description: Creates math function
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathfunctionfactory/createmathfunction/
---
## IMathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creates math function

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Return Value

new math function

## IMathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) method


Creates math function

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [System::String](../../../system/string/) | Function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Return Value

new math function

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [IMathFunctionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)