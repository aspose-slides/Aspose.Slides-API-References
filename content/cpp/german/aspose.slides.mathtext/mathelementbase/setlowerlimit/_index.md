---
title: SetLowerLimit()
second_title: Aspose.Slides für C++ API Referenz
description: Nimmt die untere Grenze
type: docs
weight: 144
url: /de/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) Methode

Nimmt die untere Grenze

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Rückgabewert

Neue Instanz vom Typ [IMathLimit](../../imathlimit/)

## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) Methode

Nimmt die untere Grenze

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Rückgabewert

Neue Instanz vom Typ [IMathLimit](../../imathlimit/)

## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLimit](../../imathlimit/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)