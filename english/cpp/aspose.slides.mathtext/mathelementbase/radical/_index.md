---
title: Radical()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the mathematical root of the given degree from the specified argument.
type: docs
weight: 118
url: /cpp/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) method


Specifies the mathematical root of the given degree from the specified argument.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument of Radical |

### Return Value

New instance of type [IMathRadical](../../imathradical/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRadical](../../imathradical/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathElementBase::Radical([System::String](../../../system/string/)) method


Specifies the mathematical root of the given degree from the specified argument.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### Return Value

New instance of type [IMathRadical](../../imathradical/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRadical](../../imathradical/)
* Class [String](../../../system/string/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
