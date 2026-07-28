---
title: InsertBefore()
second_title: Aspose.Slides C++ API referencia
description: Beszúrja a megadott csomópontot közvetlenül a megadott referencia csomópont elé.
type: docs
weight: 209
url: /hu/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) metódus


Beszúrja a megadott csomópontot közvetlenül a megadott referencia csomópont elé.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | A beszúrandó [XmlNode](../../xmlnode/). |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Az [XmlNode](../../xmlnode/), amely a referencia csomópont. **newChild** a csomópont előtt kerül elhelyezésre. |

### Visszatérési érték

A beszúrt [XmlNode](../../xmlnode/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlAttribute](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)