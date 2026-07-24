---
title: SelectSingleNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Wählt den ersten XmlNode aus, der dem XPath-Ausdruck entspricht.
type: docs
weight: 352
url: /de/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) Methode


Wählt das erste [XmlNode](../) aus, das dem [XPath](../../../system.xml.xpath/) Ausdruck entspricht.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Der [XPath](../../../system.xml.xpath/) Ausdruck. |

### Rückgabewert

Das erste [XmlNode](../), das der [XPath](../../../system.xml.xpath/) Abfrage entspricht, oder **nullptr**, wenn kein passender Knoten gefunden wird.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) Methode


Wählt das erste [XmlNode](../) aus, das dem [XPath](../../../system.xml.xpath/) Ausdruck entspricht. Alle im [XPath](../../../system.xml.xpath/) Ausdruck gefundenen Präfixe werden mithilfe des bereitgestellten [XmlNamespaceManager](../../xmlnamespacemanager/) aufgelöst.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Der [XPath](../../../system.xml.xpath/) Ausdruck. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Ein [XmlNamespaceManager](../../xmlnamespacemanager/) zur Verwendung beim Auflösen von Namespaces für Präfixe im [XPath](../../../system.xml.xpath/) Ausdruck. |

### Rückgabewert

Das erste [XmlNode](../), das der [XPath](../../../system.xml.xpath/) Abfrage entspricht, oder **nullptr**, wenn kein passender Knoten gefunden wird.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)