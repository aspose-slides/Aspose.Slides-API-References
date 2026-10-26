---
title: SetUpperLimit()
second_title: Aspose.Slides für C++ API Referenz
description: Nimmt obere Grenze
type: docs
weight: 144
url: /de/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) Methode

Nimmt obere Grenze

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Rückgabewert

Neue Instanz vom Typ [IMathLimit](../../imathlimit/)

## Bemerkungen

Beispiel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) Methode

Nimmt obere Grenze

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLimit](../../imathlimit/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)