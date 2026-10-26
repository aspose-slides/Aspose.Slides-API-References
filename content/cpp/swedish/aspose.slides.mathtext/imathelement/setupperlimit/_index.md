---
title: SetUpperLimit()
second_title: Aspose.Slides för C++ API-referens
description: Tar övre gräns
type: docs
weight: 144
url: /sv/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) metod


Tar övre gräns

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | gräns |

### Returvärde

Ny instans av typen [IMathLimit](../../imathlimit/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) metod


Tar övre gräns

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | gräns |

### Returvärde

Ny instans av typen [IMathLimit](../../imathlimit/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathLimit](../../imathlimit/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)