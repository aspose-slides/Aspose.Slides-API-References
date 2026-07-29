---
title: SelectNodes()
second_title: Aspose.Slides för C++ API-referens
description: Väljer en lista med noder som matchar XPath-uttrycket.
type: docs
weight: 365
url: /sv/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) metod


Väljer en lista med noder som matchar [XPath](../../../system.xml.xpath/)-uttrycket.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/)-uttrycket. |

### Returvärde

Ett [XmlNodeList](../../xmlnodelist/) som innehåller en samling av noder som matchar [XPath](../../../system.xml.xpath/)-frågan.

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metod


Väljer en lista med noder som matchar [XPath](../../../system.xml.xpath/)-uttrycket. Alla prefix som finns i [XPath](../../../system.xml.xpath/)-uttrycket löses upp med den medföljande [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | [XPath](../../../system.xml.xpath/)-uttrycket. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Ett [XmlNamespaceManager](../../xmlnamespacemanager/) som används för att lösa namnrymder för prefix i [XPath](../../../system.xml.xpath/)-uttrycket. |

### Returvärde

Ett [XmlNodeList](../../xmlnodelist/) som innehåller en samling av noder som matchar [XPath](../../../system.xml.xpath/)-frågan.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNodeList](../../xmlnodelist/)
* Klass [String](../../../system/string/)
* Klass [XmlNode](../)
* Klass [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)