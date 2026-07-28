---
title: SetNamedItem()
second_title: Aspose.Slides C++ API referencia
description: "Hozzáad egy XmlNode-ot a XmlNode::get_Name értékével."
type: docs
weight: 27
url: /hu/system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) method

Hozzáad egy [XmlNode](../../xmlnode/) a [XmlNode::get_Name](../../xmlnode/get_name/) értékével.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Egy [XmlNode](../../xmlnode/) a [XmlNamedNodeMap](../) tárolására. Ha a térképben már létezik olyan nevű csomópont, akkor azt az újval cseréli le. |

### Visszatérési érték

Ha a **node** lecserél egy már létező, azonos nevű csomópontot, akkor a régi csomópont kerül visszaadásra; egyébként a **nullptr** kerül visszaadásra.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlNamedNodeMap](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)