---
title: InsertAfter()
second_title: Aspose.Slides for C++ API referenciája
description: Beilleszti a megadott csomópontot közvetlenül a megadott referencia-csomópont után.
type: docs
weight: 222
url: /hu/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metódus


Beilleszti a megadott csomópontot közvetlenül a megadott referencia-csomópont után.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | A [XmlNode](../../xmlnode/) a beszúráshoz. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | A [XmlNode](../../xmlnode/), amely a referencia-csomópont. A **newChild** a **refChild** után kerül elhelyezésre. |

### Visszatérési érték

A [XmlNode](../../xmlnode/) beszúrt.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlAttribute](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)