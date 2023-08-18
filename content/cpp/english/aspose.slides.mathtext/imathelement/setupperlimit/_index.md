---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API Reference
description: Takes upper limit
type: docs
weight: 144
url: /aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) method


Takes upper limit

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Return Value

New instance of type [IMathLimit](../../imathlimit/)
## Remarks



Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) method


Takes upper limit

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)