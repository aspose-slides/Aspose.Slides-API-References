---
title: WriteStartAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft het begin van een attribuut met de opgegeven lokale naam en namespace-URI.
type: docs
weight: 144
url: /nl/system.xml/xmlwriter/writestartattribute/
---
## XmlWriter::WriteStartAttribute(const String\&, const String\&) methode

Schrijft het begin van een attribuut met de opgegeven lokale naam en namespace-URI.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName, const String &ns)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het attribuut. |
| ns | const [String](../../../system/string/)\& | De namespace-URI van het attribuut. |

## XmlWriter::WriteStartAttribute(const String\&, const String\&, const String\&) methode

Wanneer overschreven in een afgeleide klasse, schrijft het het begin van een attribuut met het opgegeven prefix, de lokale naam en de namespace-URI.

```cpp
virtual void System::Xml::XmlWriter::WriteStartAttribute(const String &prefix, const String &localName, const String &ns)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Het namespace-prefix van het attribuut. |
| localName | const [String](../../../system/string/)\& | De lokale naam van het attribuut. |
| ns | const [String](../../../system/string/)\& | De namespace-URI voor het attribuut. |

## XmlWriter::WriteStartAttribute(const String\&) methode

Schrijft het begin van een attribuut met de opgegeven lokale naam.

```cpp
void System::Xml::XmlWriter::WriteStartAttribute(const String &localName)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het attribuut. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)