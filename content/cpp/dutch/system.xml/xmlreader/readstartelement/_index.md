---
title: ReadStartElement()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of het huidige knooppunt een element is en beweegt de lezer naar het volgende knooppunt.
type: docs
weight: 846
url: /nl/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() methode

Controleert of het huidige knooppunt een element is en beweegt de lezer naar het volgende knooppunt.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) methode

Controleert of het huidige inhoudsknooppunt een element is met de opgegeven [XmlReader::get_Name](../get_name/) waarde en beweegt de lezer naar het volgende knooppunt.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het element. |

## XmlReader::ReadStartElement(String, String) methode

Controleert of het huidige inhoudsknooppunt een element is met de opgegeven [XmlReader::get_LocalName](../get_localname/) en [XmlReader::get_NamespaceURI](../get_namespaceuri/) waarden en beweegt de lezer naar het volgende knooppunt.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localname | [String](../../../system/string/) | De lokale naam van het element. |
| ns | [String](../../../system/string/) | De namespace-URI van het element. |

## Zie ook

* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)