---
title: SetLowerLimit()
second_title: Aspose.Slides för C++ API-referens
description: Tar lägre gräns
type: docs
weight: 144
url: /sv/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) metod


Tar lägre gräns

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | gräns |

### Returvärde

Ny instans av typen [IMathLimit](../../imathlimit/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) metod


Tar lägre gräns

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
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
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathLimit](../../imathlimit/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)