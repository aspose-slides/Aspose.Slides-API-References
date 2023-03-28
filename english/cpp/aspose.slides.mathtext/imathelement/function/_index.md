---
title: Function()
second_title: Aspose.Slides for C++ API Reference
description: Takes a function of an argument using this instance as the function name
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\>) method


Takes a function of an argument using this instance as the function name

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | An argument of the function |

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
* Class [IMathElement](../)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## IMathElement::Function([System::String](../../../system/string/)) method


Takes a function of an argument using this instance as the function name

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
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
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
