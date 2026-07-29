---
title: SelectSingleNode()
second_title: Aspose.Slides för C++ API-referens
description: Väljer den första XmlNode som matchar XPath-uttrycket.
type: docs
weight: 352
url: /sv/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) metod

Väljer den första [XmlNode](../) som matchar [XPath](../../../system.xml.xpath/)-uttrycket.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Det [XPath](../../../system.xml.xpath/)-uttrycket. |

### Returvärde

Den första [XmlNode](../) som matchar [XPath](../../../system.xml.xpath/)-frågan eller **nullptr** om ingen matchande nod hittas.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metod

Väljer den första [XmlNode](../) som matchar [XPath](../../../system.xml.xpath/)-uttrycket. Alla prefix som finns i [XPath](../../../system.xml.xpath/)-uttrycket löses upp med hjälp av den medföljande [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Det [XPath](../../../system.xml.xpath/)-uttrycket. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | En [XmlNamespaceManager](../../xmlnamespacemanager/) som används för att lösa namnrymder för prefix i [XPath](../../../system.xml.xpath/)-uttrycket. |

### Returvärde

Den första [XmlNode](../) som matchar [XPath](../../../system.xml.xpath/)-frågan eller **nullptr** om ingen matchande nod hittas.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../)
* Klass [String](../../../system/string/)
* Klass [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)