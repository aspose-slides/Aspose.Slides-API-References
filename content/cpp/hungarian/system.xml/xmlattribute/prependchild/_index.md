---
title: PrependChild()
second_title: Aspose.Slides for C++ API Referencia
description: Hozzáadja a megadott csomópontot ennek a csomópontnak a gyermekcsomópontok listájának elejéhez.
type: docs
weight: 261
url: /hu/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) metódus


Hozzáadja a megadott csomópontot ennek a csomópontnak a gyermekcsomópontok listájának elejéhez.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | A hozzáadandó [XmlNode](../../xmlnode/). Ha egy [XmlDocumentFragment](../../xmldocumentfragment/), akkor a dokumentumfragment teljes tartalma átkerül ennek a csomópontnak a gyermeklistájába. |

### Visszatérési érték

A [XmlNode](../../xmlnode/) hozzáadva.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlAttribute](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)