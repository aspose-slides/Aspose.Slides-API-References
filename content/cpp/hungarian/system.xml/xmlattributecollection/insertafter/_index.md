---
title: InsertAfter()
second_title: Aspose.Slides C++ API referencia
description: Beszúrja a megadott attribútumot közvetlenül a megadott referencia attribútum után.
type: docs
weight: 66
url: /hu/system.xml/xmlattributecollection/insertafter/
---
## XmlAttributeCollection::InsertAfter(const SharedPtr\<XmlAttribute\>\&, const SharedPtr\<XmlAttribute\>\&) method

Beszúrja a megadott attribútumot közvetlenül a megadott referencia attribútum után.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::InsertAfter(const SharedPtr<XmlAttribute> &newNode, const SharedPtr<XmlAttribute> &refNode)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | A beszúrni kívánt attribútum. |
| refNode | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | A referencia attribútum. **newNode** a **refNode** után kerül elhelyezésre. |

### Visszatérési érték

A [XmlAttribute](../../xmlattribute/) a gyűjteménybe való beszúráshoz.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlAttribute](../../xmlattribute/)
* Osztály [XmlAttributeCollection](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)