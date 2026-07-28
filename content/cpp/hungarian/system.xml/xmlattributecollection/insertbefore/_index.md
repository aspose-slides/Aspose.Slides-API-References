---
title: InsertBefore()
second_title: Aspose.Slides for C++ API referencia
description: Beszúrja a megadott attribútumot közvetlenül a megadott referenciaattribútum elé.
type: docs
weight: 53
url: /hu/system.xml/xmlattributecollection/insertbefore/
---
## XmlAttributeCollection::InsertBefore(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) metódus


Beszúrja a megadott attribútumot közvetlenül a megadott referenciaattribútum elé.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertBefore(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | A beillesztendő attribútum. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | A referencia attribútum. **newNode** kerül a **refNode** elé. |

### Visszatérési érték

A [XmlAttribute](../../xmlattribute/) a gyűjteménybe való beszúráshoz.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlAttribute](../../xmlattribute/)
* Osztály [XmlAttributeCollection](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)