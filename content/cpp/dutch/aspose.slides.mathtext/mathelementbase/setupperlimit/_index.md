---
title: SetUpperLimit()
second_title: Aspose.Slides voor C++ API-referentie
description: Neemt de bovenlimiet
type: docs
weight: 131
url: /nl/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) methode


Neemt de bovenlimiet

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Retourwaarde

Nieuwe instantie van type [IMathLimit](../../imathlimit/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) methode


Neemt de bovenlimiet

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Retourwaarde

Nieuwe instantie van type [IMathLimit](../../imathlimit/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLimit](../../imathlimit/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)