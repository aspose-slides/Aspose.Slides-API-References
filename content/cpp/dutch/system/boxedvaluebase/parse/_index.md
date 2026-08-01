---
title: Parse()
second_title: Aspose.Slides voor C++ API Referentie
description: Boxt de waarde van een enumeratie-constante van de opgegeven enumeratie met de opgegeven naam. Een parameter geeft aan of hoofdlettergebruik moet worden genegeerd bij het interpreteren van de tekenreeks die de naam van de enumeratie-constante specificeert.
type: docs
weight: 53
url: /nl/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) methode

Boxt de waarde van een enumeratie-constante van de opgegeven enumeratie met de opgegeven naam. Een parameter geeft aan of hoofdlettergebruik moet worden genegeerd bij het interpreteren van de tekenreeks die de naam van de enumeratie-constante specificeert.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Specificeert het type van de enumeratie |
| str | const [String](../../string/)\& | De naam van de enumeratie-constante waarvan de waarde moet worden ge-boxt |
| ignoreCase | **bool** | Geeft aan of hoofdlettergebruik moet worden genegeerd bij het interpreteren van de tekenreeks die de naam van de enumeratie-constante weergeeft |

### Retourwaarde

Een gedeelde pointer naar het object dat de ge-boxte waarde van de opgegeven enumeratie-constante vertegenwoordigt

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) methode

Boxt de waarde van een enumeratie-constante van de opgegeven enumeratie met de opgegeven naam.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Specificeert het type van de enumeratie |
| str | const [String](../../string/)\& | De naam van de enumeratie-constante waarvan de waarde moet worden ge-boxt |

### Retourwaarde

Een gedeelde pointer naar het object dat de ge-boxte waarde van de opgegeven enumeratie-constante vertegenwoordigt

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [String](../../string/)
* Klasse [BoxedValueBase](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)