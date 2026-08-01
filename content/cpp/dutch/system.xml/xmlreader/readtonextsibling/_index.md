---
title: ReadToNextSibling()
second_title: Aspose.Slides voor C++ API-referentie
description: Verplaatst de XmlReader naar het volgende broerelement met de opgegeven gekwalificeerde naam.
type: docs
weight: 924
url: /nl/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) methode


Verplaatst de [XmlReader](../) naar het volgende broerelement met de opgegeven gekwalificeerde naam.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het broerelement waarnaar u wilt verplaatsen. |

### Returnwaarde

**true** als een overeenkomend broerelement wordt gevonden; anders **false**. Als er geen overeenkomend broerelement wordt gevonden, wordt de [XmlReader](../) gepositioneerd op de eindtag (de waarde van [XmlReader::get_NodeType](../get_nodetype/) is [XmlNodeType::EndElement](../../xmlnodetype/)) van het bovenliggende element.

## XmlReader::ReadToNextSibling(String, String) methode


Verplaatst de [XmlReader](../) naar het volgende broerelement met de opgegeven lokale naam en namespace-URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het broerelement waarnaar u wilt verplaatsen. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het broerelement waarnaar u wilt verplaatsen. |

### Returnwaarde

**true** als een overeenkomend broerelement wordt gevonden; anders **false**. Als er geen overeenkomend broerelement wordt gevonden, wordt de [XmlReader](../) gepositioneerd op de eindtag (de waarde van [XmlReader::get_NodeType](../get_nodetype/) is [XmlNodeType::EndElement](../../xmlnodetype/)) van het bovenliggende element.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)