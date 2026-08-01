---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Probeert de opgegeven tekenreeks om te zetten naar een gelijkwaardige enum-constante.
type: docs
weight: 79
url: /nl/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) methode

Probeert de opgegeven tekenreeks om te zetten naar een overeenkomstige enum-constante.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) die wordt geïnterpreteerd als de naam van een enum-constante |
| result | E\& | De uitvoerparameter die, indien de conversie slaagt, het resultaat van de conversie bevat |

### Retourwaarde

True als conversie slaagt, anders - false

## Enum::TryParse(const String\&, bool, E\&) methode

Probeert de opgegeven tekenreeks om te zetten naar een overeenkomstige enum-constante.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) die wordt geïnterpreteerd als de naam van een enum-constante |
| ignoreCase | **bool** | Specificeert of hoofdlettergebruik moet worden genegeerd bij het interpreteren van de tekenreeks |
| result | E\& | De uitvoerparameter die, indien de conversie slaagt, het resultaat van de conversie bevat bij de retour van de functie |

### Retourwaarde

True als conversie slaagt, anders - false

## Zie ook

* Klasse [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)