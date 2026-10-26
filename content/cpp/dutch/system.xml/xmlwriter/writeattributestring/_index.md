---
title: WriteAttributeString()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, schrijft een attribuut met de opgegeven lokale naam, namespace-URI en waarde.
type: docs
weight: 131
url: /nl/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) methode

Wanneer overschreven in een afgeleide klasse, schrijft een attribuut met de opgegeven lokale naam, namespace-URI en waarde.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het attribuut. |
| ns | const [String](../../../system/string/)\& | De namespace-URI die aan het attribuut moet worden gekoppeld. |
| value | const [String](../../../system/string/)\& | De waarde van het attribuut. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) methode

Wanneer overschreven in een afgeleide klasse, schrijft het attribuut met de opgegeven lokale naam en waarde.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het attribuut. |
| value | const [String](../../../system/string/)\& | De waarde van het attribuut. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) methode

Wanneer overschreven in een afgeleide klasse, schrijft het attribuut met het opgegeven voorvoegsel, de lokale naam, de namespace-URI en de waarde.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Het namespace-voorvoegsel van het attribuut. |
| localName | const [String](../../../system/string/)\& | De lokale naam van het attribuut. |
| ns | const [String](../../../system/string/)\& | De namespace-URI van het attribuut. |
| value | const [String](../../../system/string/)\& | De waarde van het attribuut. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlWriter](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)