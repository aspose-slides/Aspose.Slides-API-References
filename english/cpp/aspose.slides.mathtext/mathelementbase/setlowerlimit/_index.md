---
title: SetLowerLimit()
second_title: Aspose.Slides for C++ API Reference
description: Takes lower limit
type: docs
weight: 144
url: /cpp/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) method


Takes lower limit

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Return Value

New instance of type [IMathLimit](../../imathlimit/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) method


Takes lower limit

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Return Value

New instance of type [IMathLimit](../../imathlimit/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)