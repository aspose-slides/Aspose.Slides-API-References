---
title: SelectNodes()
second_title: Aspose.Slides pro C++ API Reference
description: Vybere seznam uzlů odpovídajících výrazu XPath.
type: docs
weight: 365
url: /cs/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) method


Vybere seznam uzlů odpovídajících výrazu [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Výraz [XPath](../../../system.xml.xpath/). |

### Návratová hodnota

[XmlNodeList](../../xmlnodelist/) obsahující kolekci uzlů odpovídajících dotazu [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) method


Vybere seznam uzlů odpovídajících výrazu [XPath](../../../system.xml.xpath/). Všechny předpony nalezené ve výrazu [XPath](../../../system.xml.xpath/) jsou vyřešeny pomocí poskytnutého [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Výraz [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) použité k řešení jmenných prostor pro předpony ve výrazu [XPath](../../../system.xml.xpath/). |

### Návratová hodnota

[XmlNodeList](../../xmlnodelist/) obsahující kolekci uzlů odpovídajících dotazu [XPath](../../../system.xml.xpath/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNodeList](../../xmlnodelist/)
* Třída [String](../../../system/string/)
* Třída [XmlNode](../)
* Třída [XmlNamespaceManager](../../xmlnamespacemanager/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)