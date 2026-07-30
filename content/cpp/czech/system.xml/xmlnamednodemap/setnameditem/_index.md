---
title: SetNamedItem()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Přidá XmlNode pomocí jeho hodnoty XmlNode::get_Name."
type: docs
weight: 27
url: /cs/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) metoda

Přidá [XmlNode](../../xmlnode/) pomocí jeho [XmlNode::get_Name](../../xmlnode/get_name/) hodnoty.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Objekt [XmlNode](../../xmlnode/) k uložení do [XmlNamedNodeMap](../). Pokud je v mapě již přítomen uzel se stejným názvem, je nahrazen novým. |

### Návratová hodnota

Pokud **node** nahradí existující uzel se stejným názvem, vrátí se starý uzel; jinak se vrátí **nullptr**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlNamedNodeMap](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)