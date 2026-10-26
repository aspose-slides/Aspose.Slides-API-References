---
title: ReadToDescendant()
second_title: Aspose.Slides voor C++ API-referentie
description: Verplaatst de XmlReader naar het volgende afstammende element met de opgegeven gekwalificeerde naam.
type: docs
weight: 911
url: /nl/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) methode

Verplaatst de [XmlReader](../) naar het volgende afstammende element met de opgegeven gekwalificeerde naam.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | [String](../../../system/string/) | De gekwalificeerde naam van het element waarnaar u wilt verplaatsen. |

### Retourwaarde

**true** als een overeenkomend afstammend element wordt gevonden; anders **false**. Als er geen overeenkomend kindelement wordt gevonden, wordt de [XmlReader](../) gepositioneerd op de eindtag ([XmlReader::get_NodeType](../get_nodetype/) waarde is [XmlNodeType::EndElement](../../xmlnodetype/)) van het element. Als de [XmlReader](../) niet op een element is gepositioneerd wanneer [XmlReader::ReadToDescendant(String)](./) werd aangeroepen, retourneert deze methode **false** en wordt de positie van de [XmlReader](../) niet gewijzigd.

## XmlReader::ReadToDescendant(String, String) methode

Verplaatst de [XmlReader](../) naar het volgende afstammende element met de opgegeven lokale naam en namespace-URI.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | [String](../../../system/string/) | De lokale naam van het element waarnaar u wilt verplaatsen. |
| namespaceURI | [String](../../../system/string/) | De namespace-URI van het element waarnaar u wilt verplaatsen. |

### Retourwaarde

**true** als een overeenkomend afstammend element wordt gevonden; anders **false**. Als er geen overeenkomend kindelement wordt gevonden, wordt de [XmlReader](../) gepositioneerd op de eindtag ([XmlReader::get_NodeType](../get_nodetype/) waarde is [XmlNodeType::EndElement](../../xmlnodetype/)) van het element. Als de [XmlReader](../) niet op een element is gepositioneerd wanneer [XmlReader::ReadToDescendant(String,String)](./) werd aangeroepen, retourneert deze methode **false** en wordt de positie van de [XmlReader](../) niet gewijzigd.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)