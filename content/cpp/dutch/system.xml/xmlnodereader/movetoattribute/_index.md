---
title: MoveToAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: Verplaatst zich naar het attribuut met de opgegeven naam.
type: docs
weight: 300
url: /nl/system.xml/xmlnodereader/movetoattribute/
---
## XmlNodeReader::MoveToAttribute(String) methode


Verplaatst zich naar het attribuut met de opgegeven naam.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het attribuut. |

### Retourwaarde

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlNodeReader::MoveToAttribute(String, String) methode


Verplaatst zich naar het attribuut met de opgegeven lokale naam en namespace-URI.

```cpp
bool System::Xml::XmlNodeReader::MoveToAttribute(String name, String namespaceURI) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

**true** if the attribute is found; otherwise, **false**. If **false**, the reader's position does not change.

## XmlNodeReader::MoveToAttribute(int32_t) methode


Verplaatst zich naar het attribuut met de opgegeven index.

```cpp
void System::Xml::XmlNodeReader::MoveToAttribute(int32_t attributeIndex) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| attributeIndex | **int32_t** | De index van het attribuut. |

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlNodeReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)