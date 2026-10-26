---
title: SetNamedItem()
second_title: Aspose.Slides dla C++ API Reference
description: "Dodaje XmlNode przy użyciu jego wartości XmlNode::get_Name."
type: docs
weight: 27
url: /pl/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) metoda


Dodaje [XmlNode](../../xmlnode/) przy użyciu wartości [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Obiekt [XmlNode](../../xmlnode/) do przechowywania w [XmlNamedNodeMap](../). Jeśli w mapie istnieje już węzeł o tej nazwie, zostaje on zastąpiony nowym. |

### Wartość zwracana

Jeśli **node** zastępuje istniejący węzeł o tej samej nazwie, zwracany jest stary węzeł; w przeciwnym razie zwracany jest **nullptr**.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [XmlNamedNodeMap](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)