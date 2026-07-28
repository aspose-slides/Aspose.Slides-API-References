---
title: Item()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja a megadott indexű csomópontot az XmlNamedNodeMap-ben.
type: docs
weight: 53
url: /hu/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) metódus


Visszaadja a megadott indexű csomópontot a(z) [XmlNamedNodeMap](../)-ban.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A lekérendő csomópont indexe a(z) [XmlNamedNodeMap](../)-ben. Az index nullártol kezdődik; ezért az első csomópont indexe 0 és az utolsó csomópont indexe [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Visszatérési érték

A megadott indexnél lévő [XmlNode](../../xmlnode/). Ha a **index** kisebb, mint 0, vagy nagyobb vagy egyenlő a [XmlNamedNodeMap::get_Count](../get_count/) értéknél, **nullptr** lesz visszaadva.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlNamedNodeMap](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)