---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Referentie
description: Verplaatst zich naar het attribuut met de opgegeven naam.
type: docs
weight: 456
url: /nl/system.xml/xmlvalidatingreader/movetoattribute/
---
## XmlValidatingReader::MoveToAttribute(String) method


Verplaatst zich naar het attribuut met de opgegeven naam.

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String name) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het attribuut. |

### Retourwaarde

**true** als het attribuut wordt gevonden; anders **false**. Als **false**, verandert de positie van de lezer niet.

## XmlValidatingReader::MoveToAttribute(String, String) method


Verplaatst zich naar het attribuut met de opgegeven lokale naam en namespace Uniform Resource Identifier (URI).

```cpp
bool System::Xml::XmlValidatingReader::MoveToAttribute(String localName, String namespaceURI) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

**true** als het attribuut wordt gevonden; anders **false**. Als **false**, verandert de positie van de lezer niet.

## XmlValidatingReader::MoveToAttribute(int32_t) method


Verplaatst zich naar het attribuut met de opgegeven index.

```cpp
void System::Xml::XmlValidatingReader::MoveToAttribute(int32_t i) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | **int32_t** | De index van het attribuut. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlValidatingReader](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)