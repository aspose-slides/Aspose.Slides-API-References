---
title: SetNamedItem()
second_title: Aspose.Slides C++ API hivatkozás
description: "Hozzáad egy XmlNode-ot az XmlNode::get_Name eredményével."
type: docs
weight: 14
url: /hu/system.xml/xmlattributecollection/setnameditem/
---
## XmlAttributeCollection::SetNamedItem(SharedPtr\<XmlNode\>) metódus

Hozzáad egy [XmlNode](../../xmlnode/) a [XmlNode::get_Name](../../xmlnode/get_name/) eredményével.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttributeCollection::SetNamedItem(SharedPtr<XmlNode> node) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Egy attribútum node a gyűjteményben tároláshoz. A node később a node neve alapján lesz elérhető. Ha egy node ezzel a névvel már létezik a gyűjteményben, akkor azt az újval cserélik; egyébként a node a gyűjtemény végére kerül hozzáadásra. |

### Visszatérési érték

Ha a **node** helyettesít egy már létező, azonos nevű node-ot, akkor a régi node kerül visszaadásra; egyébként a hozzáadott node kerül visszaadásra.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlAttributeCollection](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)