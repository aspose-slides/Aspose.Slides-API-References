---
title: SelectNodes()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wybiera listę węzłów pasujących do wyrażenia XPath.
type: docs
weight: 365
url: /pl/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) metoda

Wybiera listę węzłów pasujących do wyrażenia [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Wyrażenie [XPath](../../../system.xml.xpath/). |

### Wartość zwracana

Obiekt [XmlNodeList](../../xmlnodelist/) zawierający kolekcję węzłów pasujących do zapytania [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metoda

Wybiera listę węzłów pasujących do wyrażenia [XPath](../../../system.xml.xpath/). Wszystkie prefiksy znalezione w wyrażeniu [XPath](../../../system.xml.xpath/) są rozwiązywane przy użyciu dostarczonego [XmlNamespaceManager](../../xmlnamespacemanager/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Wyrażenie [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Obiekt [XmlNamespaceManager](../../xmlnamespacemanager/) używany do rozwiązywania przestrzeni nazw dla prefiksów w wyrażeniu [XPath](../../../system.xml.xpath/). |

### Wartość zwracana

Obiekt [XmlNodeList](../../xmlnodelist/) zawierający kolekcję węzłów pasujących do zapytania [XPath](../../../system.xml.xpath/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNodeList](../../xmlnodelist/)
* Klasa [String](../../../system/string/)
* Klasa [XmlNode](../)
* Klasa [XmlNamespaceManager](../../xmlnamespacemanager/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)