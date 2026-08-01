---
title: SelectNodes()
second_title: Aspose.Slides voor C++ API-referentie
description: Selecteert een lijst met knooppunten die overeenkomen met de XPath-expressie.
type: docs
weight: 365
url: /nl/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) methode


Selecteert een lijst met knooppunten die overeenkomen met de [XPath](../../../system.xml.xpath/)-expressie.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | De [XPath](../../../system.xml.xpath/)-expressie. |

### Retourwaarde

Een [XmlNodeList](../../xmlnodelist/) met een verzameling knooppunten die overeenkomen met de [XPath](../../../system.xml.xpath/)-query.

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) methode


Selecteert een lijst met knooppunten die overeenkomen met de [XPath](../../../system.xml.xpath/)-expressie. Alle in de [XPath](../../../system.xml.xpath/)-expressie gevonden prefixen worden opgelost met behulp van de opgegeven [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | De [XPath](../../../system.xml.xpath/)-expressie. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Een [XmlNamespaceManager](../../xmlnamespacemanager/) die wordt gebruikt voor het oplossen van namespaces voor prefixen in de [XPath](../../../system.xml.xpath/)-expressie. |

### Retourwaarde

Een [XmlNodeList](../../xmlnodelist/) met een verzameling knooppunten die overeenkomen met de [XPath](../../../system.xml.xpath/)-query.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNodeList](../../xmlnodelist/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNode](../)
* Klasse [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)