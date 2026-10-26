---
title: SelectNodes()
second_title: Aspose.Slides für C++ API-Referenz
description: Wählt eine Liste von Knoten aus, die dem XPath-Ausdruck entsprechen.
type: docs
weight: 365
url: /de/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) Methode

Wählt eine Liste von Knoten aus, die dem [XPath](../../../system.xml.xpath/) Ausdruck entsprechen.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Der [XPath](../../../system.xml.xpath/) Ausdruck. |

### Rückgabewert

Ein [XmlNodeList](../../xmlnodelist/) mit einer Sammlung von Knoten, die der [XPath](../../../system.xml.xpath/) Abfrage entsprechen.

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) Methode

Wählt eine Liste von Knoten aus, die dem [XPath](../../../system.xml.xpath/) Ausdruck entsprechen. Alle in dem [XPath](../../../system.xml.xpath/) Ausdruck gefundenen Präfixe werden mithilfe des bereitgestellten [XmlNamespaceManager](../../xmlnamespacemanager/) aufgelöst.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Der [XPath](../../../system.xml.xpath/) Ausdruck. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Ein [XmlNamespaceManager](../../xmlnamespacemanager/) zum Auflösen von Namespaces für Präfixe im [XPath](../../../system.xml.xpath/) Ausdruck. |

### Rückgabewert

Ein [XmlNodeList](../../xmlnodelist/) mit einer Sammlung von Knoten, die der [XPath](../../../system.xml.xpath/) Abfrage entsprechen.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNodeList](../../xmlnodelist/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)