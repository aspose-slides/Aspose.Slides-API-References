---
title: SetNamedItem()
second_title: Aspose.Slides pro C++ API Reference
description: "Přidá XmlNode pomocí výsledku XmlNode::get_Name."
type: docs
weight: 14
url: /cs/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) metoda

Přidá [XmlNode](../../xmlnode/) pomocí jeho [XmlNode::get_Name](../../xmlnode/get_name/) výsledku.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Uzel atributu, který se má uložit v této kolekci. Node bude později přístupný pomocí názvu node. Pokud je v kolekci již node s tímto názvem, bude nahrazen novým; jinak bude node připojen na konec kolekce. |

### Návratová hodnota

Pokud **node** nahradí existující node se stejným názvem, bude vrácen starý node; jinak bude vrácen přidaný node.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)