---
title: GetNamedItem()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Pobiera węzeł XmlNode określony nazwą.
type: docs
weight: 14
url: /pl/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) metoda

Zwraca [XmlNode](../../xmlnode/) określony nazwą.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa węzła do pobrania. Jest porównywana z wartością [XmlNode::get_Name](../../xmlnode/get_name/) dopasowanego węzła. |

### Wartość zwracana

Obiekt [XmlNode](../../xmlnode/) o określonej nazwie lub **nullptr**, jeśli nie znaleziono pasującego węzła.

## XmlNamedNodeMap::GetNamedItem(String, String) metoda

Pobiera węzeł z pasującymi wartościami [XmlNode::get_LocalName](../../xmlnode/get_localname/) i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa węzła do pobrania. |
| namespaceURI | [String](../../../system/string/) | Identyfikator Uniform Resource Identifier (URI) przestrzeni nazw węzła do pobrania. |

### Wartość zwracana

[XmlNode](../../xmlnode/) z pasującą lokalną nazwą i URI przestrzeni nazw lub **nullptr**, jeśli nie znaleziono pasującego węzła.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [String](../../../system/string/)
* Klasa [XmlNamedNodeMap](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)