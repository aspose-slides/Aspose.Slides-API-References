---
title: RemoveNamedItem()
second_title: Aspose.Slides dla C++ Referencja API
description: Usuwa węzeł z XmlNamedNodeMap.
type: docs
weight: 40
url: /pl/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) metoda

Usuwa węzeł z [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa węzła do usunięcia. Nazwa jest porównywana z wartością [XmlNode::get_Name](../../xmlnode/get_name/) dopasowanego węzła. |

### Wartość zwracana

Usunięty [XmlNode](../../xmlnode/) z tego [XmlNamedNodeMap](../) lub **nullptr** jeśli nie znaleziono pasującego węzła.

## XmlNamedNodeMap::RemoveNamedItem(String, String) metoda

Usuwa węzeł o dopasowanych wartościach [XmlNode::get_LocalName](../../xmlnode/get_localname/) i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa węzła do usunięcia. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw węzła do usunięcia. |

### Wartość zwracana

Usunięty [XmlNode](../../xmlnode/) lub **nullptr** jeśli nie znaleziono pasującego węzła.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [String](../../../system/string/)
* Klasa [XmlNamedNodeMap](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)