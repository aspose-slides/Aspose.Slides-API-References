---
title: MoveToAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Verplaatst zich naar het attribuut met de opgegeven naam.
type: docs
weight: 508
url: /nl/system.xml/xmltextreader/movetoattribute/
---
## XmlTextReader::MoveToAttribute(String) methode

Verplaatst zich naar het attribuut met de opgegeven naam.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String name) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De volledige naam van het attribuut. |

### Retourwaarde

**true** als het attribuut wordt gevonden; anders **false**. Als **false**, verandert de positie van de lezer niet.

## XmlTextReader::MoveToAttribute(String, String) methode

Verplaatst zich naar het attribuut met de opgegeven lokale naam en namespace-URI.

```cpp
bool System::Xml::XmlTextReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

**true** als het attribuut wordt gevonden; anders **false**. Als **false**, verandert de positie van de lezer niet.

## XmlTextReader::MoveToAttribute(int32_t) methode

Verplaatst zich naar het attribuut met de opgegeven index.

```cpp
void System::Xml::XmlTextReader::MoveToAttribute(int32_t i) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | **int32_t** | De index van het attribuut. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlTextReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)