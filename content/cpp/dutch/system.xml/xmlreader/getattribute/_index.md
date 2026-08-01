---
title: GetAttribute()
second_title: Aspose.Slides voor C++ API-referentie
description: "Wanneer deze wordt overschreven in een afgeleide klasse, haalt de waarde op van het attribuut met de opgegeven XmlReader::get_Name waarde."
type: docs
weight: 599
url: /nl/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) methode

Wanneer deze wordt overschreven in een afgeleide klasse, haalt de waarde op van het attribuut met de opgegeven [XmlReader::get_Name](../get_name/) waarde.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut. Als het attribuut niet wordt gevonden of de waarde [String::Empty](../../../system/string/empty/) is, wordt **nullptr** geretourneerd.

## XmlReader::GetAttribute(String, String) methode

Wanneer deze wordt overschreven in een afgeleide klasse, haalt de waarde op van het attribuut met de opgegeven [XmlReader::get_LocalName](../get_localname/) en [XmlReader::get_NamespaceURI](../get_namespaceuri/) waarden.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De lokale naam van het attribuut. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het attribuut. |

### Retourwaarde

De waarde van het opgegeven attribuut. Als het attribuut niet wordt gevonden of de waarde [String::Empty](../../../system/string/empty/) is, wordt **nullptr** geretourneerd. Deze methode verplaatst de lezer niet.

## XmlReader::GetAttribute(int32_t) methode

Wanneer deze wordt overschreven in een afgeleide klasse, haalt de waarde op van het attribuut met de opgegeven index.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| i | **int32_t** | De index van het attribuut. De index is nul-gebaseerd. (Het eerste attribuut heeft index 0.) |

### Retourwaarde

De waarde van het opgegeven attribuut. Deze methode verplaatst de lezer niet.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)