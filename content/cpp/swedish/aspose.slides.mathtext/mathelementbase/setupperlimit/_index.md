---
title: SetUpperLimit()
second_title: Aspose.Slides för C++ API-referens
description: Tar den övre gränsen
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) metod

Tar den övre gränsen

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | gräns |

### Returvärde

Ny instans av typ [IMathLimit](../../imathlimit/)

## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) metod

Tar den övre gränsen

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | gräns |

### Returvärde

Ny instans av typ [IMathLimit](../../imathlimit/)

## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathLimit](../../imathlimit/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)