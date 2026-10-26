---
title: SetAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de waarde van het attribuut in met de opgegeven naam.
type: docs
weight: 222
url: /nl/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) methode

Stelt de waarde van het attribuut in met de opgegeven naam.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De naam van het attribuut om te maken of te wijzigen. Dit is een gekwalificeerde naam. Als de naam een dubbele punt bevat, wordt deze geparsed in prefix- en lokale naamcomponenten. |
| value | [String](../../../system/string/) | De waarde die voor het attribuut moet worden ingesteld. |

## XmlElement::SetAttribute(String, String, String) methode

Stelt de waarde van het attribuut in met de opgegeven lokale naam en namespace-URI.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |
| value | [String](../../../system/string/) | De waarde die voor het attribuut moet worden ingesteld. |

### Returnwaarde

De attribuutwaarde.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlElement](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)