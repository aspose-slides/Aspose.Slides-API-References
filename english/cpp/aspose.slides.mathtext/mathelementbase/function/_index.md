---
title: Function()
second_title: Aspose.Slides for C++ API Reference
description: Takes a function of an argument using this instance as the function name
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) method


Takes a function of an argument using this instance as the function name

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | An argument of the function |

### Return Value

New math element of type [IMathFunction](../../imathfunction/)
## Remarks



Example: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathElementBase::Function([System::String](../../../system/string/)) method


Takes a function of an argument using this instance as the function name

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | An argument of the function |

### Return Value

New math element of type [IMathFunction](../../imathfunction/)
## Remarks



Example: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [String](../../../system/string/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
