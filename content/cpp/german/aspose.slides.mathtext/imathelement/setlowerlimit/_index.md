---
title: SetLowerLimit()
second_title: Aspose.Slides für C++ API-Referenz
description: Nimmt den unteren Grenzwert
type: docs
weight: 157
url: /de/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) Methode

Nimmt den unteren Grenzwert

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Grenzwert |

### Rückgabewert

Neue Instanz des Typs [IMathLimit](../../imathlimit/)

## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) Methode

Nimmt den unteren Grenzwert

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | Grenzwert |

### Rückgabewert

Neue Instanz des Typs [IMathLimit](../../imathlimit/)

## Bemerkungen



Beispiel: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLimit](../../imathlimit/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)