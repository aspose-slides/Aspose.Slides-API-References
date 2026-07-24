---
title: SetUpperLimit()
second_title: Aspose.Slides für C++ API-Referenz
description: Nimmt obere Grenze
type: docs
weight: 131
url: /de/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) Methode

Nimmt obere Grenze

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Rückgabewert

Neue Instanz vom Typ [IMathLimit](../../imathlimit/)
## Anmerkungen

Beispiel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) Methode

Nimmt obere Grenze

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Rückgabewert

Neue Instanz vom Typ [IMathLimit](../../imathlimit/)
## Anmerkungen

Beispiel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLimit](../../imathlimit/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)