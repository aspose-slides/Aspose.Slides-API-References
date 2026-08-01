---
title: IsStartElement()
second_title: Aspose.Slides voor C++ API-referentie
description: "Roept XmlReader::MoveToContent aan en test of de huidige inhoudsknoop een start-tag of een lege elementtag is."
type: docs
weight: 885
url: /nl/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() methode

Roept [XmlReader::MoveToContent](../movetocontent/) aan en test of de huidige inhoudsknoop een start-tag of een lege elementtag is.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Retourwaarde

**true** als [XmlReader::MoveToContent](../movetocontent/) een start-tag of een lege elementtag vindt; **false** als een node-type anders dan [XmlNodeType::Element](../../xmlnodetype/) werd gevonden.

## XmlReader::IsStartElement(String) methode

Roept [XmlReader::MoveToContent](../movetocontent/) aan en test of de huidige inhoudsknoop een start-tag of een lege elementtag is en of de [XmlReader::get_Name](../get_name/)-waarde van het gevonden element overeenkomt met het opgegeven argument.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De string die overeenkomt met de **Name**-waarde van het gevonden element. |

### Retourwaarde

**true** als de resulterende node een element is en de **Name**-waarde overeenkomt met de opgegeven string. **false** als een node-type anders dan [XmlNodeType::Element](../../xmlnodetype/) werd gevonden of als de **Name**-waarde van het element niet overeenkomt met de opgegeven string.

## XmlReader::IsStartElement(String, String) methode

Roept [XmlReader::MoveToContent](../movetocontent/) aan en test of de huidige inhoudsknoop een start-tag of een lege elementtag is en of de [XmlReader::get_LocalName](../get_localname/)- en [XmlReader::get_NamespaceURI](../get_namespaceuri/)-waarden van het gevonden element overeenkomen met de opgegeven strings.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localname | [String](../../../system/string/) | De string die overeenkomt met de **LocalName**-waarde van het gevonden element. |
| ns | [String](../../../system/string/) | De string die overeenkomt met de **NamespaceURI**-waarde van het gevonden element. |

### Retourwaarde

**true** als de resulterende node een element is. **false** als een node-type anders dan [XmlNodeType::Element](../../xmlnodetype/) werd gevonden of als de **LocalName**- en **NamespaceURI**-waarden van het element niet overeenkomen met de opgegeven strings.

## Zie ook

* Klasse [XmlReader](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)