---
title: SetNamedItem()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: "Dodaje węzeł XmlNode, wykorzystując wynik XmlNode::get_Name."
type: docs
weight: 14
url: /pl/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) metoda


Dodaje [XmlNode](../../xmlnode/) używając wyniku [XmlNode::get_Name](../../xmlnode/get_name/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Węzeł atrybutu do przechowywania w tej kolekcji. node będzie później dostępny za pomocą nazwy node. Jeśli node o tej nazwie już znajduje się w kolekcji, zostaje zastąpiony nowym; w przeciwnym razie node jest dołączany na koniec kolekcji. |

### Wartość zwracana

Jeśli **node** zastępuje istniejący node o tej samej nazwie, zwracany jest stary node; w przeciwnym razie zwracany jest dodany node.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)