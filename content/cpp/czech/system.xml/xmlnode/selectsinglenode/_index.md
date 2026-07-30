---
title: SelectSingleNode()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Vybere první XmlNode, který odpovídá výrazu XPath.
type: docs
weight: 352
url: /cs/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) metoda

Vybere první [XmlNode](../) odpovídající výrazu [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Výraz [XPath](../../../system.xml.xpath/). |

### Návratová hodnota

První [XmlNode](../) odpovídající dotazu [XPath](../../../system.xml.xpath/) nebo **nullptr**, pokud není nalezena odpovídající uzel.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metoda

Vybere první [XmlNode](../) odpovídající výrazu [XPath](../../../system.xml.xpath/). Všechny předpony nalezené ve výrazu [XPath](../../../system.xml.xpath/) jsou rozřešeny pomocí dodaného [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Výraz [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) k použití pro rozřešení jmenných prostorů pro předpony ve výrazu [XPath](../../../system.xml.xpath/). |

### Návratová hodnota

První [XmlNode](../) odpovídající dotazu [XPath](../../../system.xml.xpath/) nebo **nullptr**, pokud není nalezena odpovídající uzel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [XmlNode](../)
* třída [String](../../../system/string/)
* třída [XmlNamespaceManager](../../xmlnamespacemanager/)
* jmenný prostor [System::Xml](../../)
* knihovna [Aspose.Slides](../../../)