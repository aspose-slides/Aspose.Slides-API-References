---
title: CreateMathFunction()
second_title: Aspose.Slides for C++ API Reference
description: Creates math function
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/mathfunctionfactory/createmathfunction/
---
## MathFunctionFactory::CreateMathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Creates math function

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| funcName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function name |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element used as a function argument |

### Return Value

new math function

## MathFunctionFactory::CreateMathFunction(System::String, System::SharedPtr\<IMathElement\>) method


Creates math function

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathFunctionFactory::CreateMathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument) override
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
* Class [MathFunctionFactory](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)