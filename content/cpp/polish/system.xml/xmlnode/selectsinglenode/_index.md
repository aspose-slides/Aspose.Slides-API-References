---
title: SelectSingleNode()
second_title: Aspose.Slides dla C++ - referencja API
description: Wybiera pierwszy węzeł XmlNode, który pasuje do wyrażenia XPath.
type: docs
weight: 352
url: /pl/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) metoda

Wybiera pierwszy [XmlNode](../) pasujący do wyrażenia [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Wyrażenie [XPath](../../../system.xml.xpath/). |

### Wartość zwracana

Pierwszy [XmlNode](../) pasujący do zapytania [XPath](../../../system.xml.xpath/) lub **nullptr**, jeśli nie znaleziono pasującego węzła.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metoda

Wybiera pierwszy [XmlNode](../) pasujący do wyrażenia [XPath](../../../system.xml.xpath/). Wszystkie prefiksy znalezione w wyrażeniu [XPath](../../../system.xml.xpath/) są rozwiązywane przy użyciu podanego [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Wyrażenie [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Obiekt [XmlNamespaceManager](../../xmlnamespacemanager/) używany do rozwiązywania przestrzeni nazw dla prefiksów w wyrażeniu [XPath](../../../system.xml.xpath/). |

### Wartość zwracana

Pierwszy [XmlNode](../) pasujący do zapytania [XPath](../../../system.xml.xpath/) lub **nullptr**, jeśli nie został znaleziony pasujący węzeł.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../)
* Klasa [String](../../../system/string/)
* Klasa [XmlNamespaceManager](../../xmlnamespacemanager/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)