---
title: SetUpperLimit()
second_title: Aspose.Slides voor C++ API-referentie
description: Neemt de bovengrens
type: docs
weight: 144
url: /nl/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) methode


Neemt de bovengrens

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Retourwaarde

Nieuwe instantie van type [IMathLimit](../../imathlimit/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) methode


Neemt de bovengrens

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
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
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)