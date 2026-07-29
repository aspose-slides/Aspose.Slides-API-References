---
title: SetLowerLimit()
second_title: Aspose.Slides för C++ API-referens
description: Tar nedre gräns
type: docs
weight: 157
url: /sv/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) metod

Tar nedre gränsen

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Returvärde

Ny instans av typen [IMathLimit](../../imathlimit/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) metod

Tar nedre gränsen

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Returvärde

Ny instans av typen [IMathLimit](../../imathlimit/)
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathLimit](../../imathlimit/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)