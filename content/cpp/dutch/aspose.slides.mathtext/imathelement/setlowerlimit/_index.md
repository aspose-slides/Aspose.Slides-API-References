---
title: SetLowerLimit()
second_title: Aspose.Slides voor C++ API-referentie
description: Neemt onderlimiet
type: docs
weight: 157
url: /nl/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) methode

Neemt onderlimiet

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limiet |

### Retourwaarde

Nieuwe instantie van type [IMathLimit](../../imathlimit/)
## Opmerkingen



Voorbeeld: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) methode

Neemt onderlimiet

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limiet |

### Retourwaarde

Nieuwe instantie van type [IMathLimit](../../imathlimit/)
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLimit](../../imathlimit/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)