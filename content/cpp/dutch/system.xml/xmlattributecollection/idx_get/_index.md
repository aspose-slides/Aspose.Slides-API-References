---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert het attribuut met de opgegeven index.
type: docs
weight: 1
url: /nl/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) methode


Retourneert het attribuut met de opgegeven index.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | **int32_t** | De index van het attribuut. |

### Retourwaarde

Het attribuut op de opgegeven index.

## XmlAttributeCollection::idx_get(const String\&) methode


Retourneert het attribuut met de opgegeven naam.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | De gekwalificeerde naam van het attribuut. |

### Retourwaarde

Het attribuut met de opgegeven naam. Als het attribuut niet bestaat, retourneert deze methode **nullptr**.

## XmlAttributeCollection::idx_get(const String\&, const String\&) methode


Retourneert het attribuut met de opgegeven lokale naam en namespace Uniform Resource Identifier (URI).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | De lokale naam van het attribuut. |
| namespaceURI | const [String](../../../system/string/)\& | De namespace-URI van het attribuut. |

### Retourwaarde

Het attribuut met de opgegeven lokale naam en namespace-URI. Als het attribuut niet bestaat, retourneert deze methode **nullptr**.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlAttribute](../../xmlattribute/)
* Klasse [XmlAttributeCollection](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)