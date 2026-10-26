---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Wanneer overschreven in een afgeleide klasse, haalt het de waarde op van het attribuut met de opgegeven index.
type: docs
weight: 612
url: /nl/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) methode


Wanneer overschreven in een afgeleide klasse, haalt de waarde op van het attribuut met de opgegeven index.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | **int32_t** | De index van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut.

## XmlReader::idx_get(String) methode


Wanneer overschreven in een afgeleide klasse, haalt de waarde op van het attribuut met de opgegeven [XmlReader::get_Name](../get_name/) waarde.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut. Als het attribuut niet wordt gevonden, wordt **nullptr** geretourneerd.

## XmlReader::idx_get(String, String) methode


Wanneer overschreven in een afgeleide klasse, haalt de waarde op van het attribuut met de opgegeven [XmlReader::get_LocalName](../get_localname/) en [XmlReader::get_NamespaceURI](../get_namespaceuri/) waarden.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut. Als het attribuut niet wordt gevonden, wordt **nullptr** geretourneerd.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)