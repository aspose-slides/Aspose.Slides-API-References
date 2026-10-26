---
title: Contains()
second_title: Aspose.Slides for C++ API hivatkozás
description: Megadja, hogy a megadott XmlSchemaObject a XmlSchemaObjectCollection-ban van-e.
type: docs
weight: 92
url: /hu/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const SharedPtr\<XmlSchemaObject\>\&) metódus


Megadja, hogy a megadott [XmlSchemaObject](../../xmlschemaobject/) a [XmlSchemaObjectCollection](../)-ban van-e.

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | A [XmlSchemaObject](../../xmlschemaobject/). |

### Visszatérési érték

**true** ha a megadott kvalifikált név a gyűjteményben van; egyébként **false** értéket ad vissza. Ha **nullptr** van megadva, **false** kerül visszaadásra, mert nincs null névvel rendelkező kvalifikált név.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchemaObject](../../xmlschemaobject/)
* Osztály [XmlSchemaObjectCollection](../)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)