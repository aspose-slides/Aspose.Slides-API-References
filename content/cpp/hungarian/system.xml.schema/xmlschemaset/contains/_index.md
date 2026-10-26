---
title: Contains()
second_title: "Aspose.Slides for C++ API-referencia"
description: "Megadja, hogy egy XML séma definíciós nyelv (XSD) séma a megadott cél-névtér URI-val az XmlSchemaSet-ben van-e."
type: docs
weight: 196
url: /hu/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) metódus


Megadja, hogy egy XML [Schema](../../) definíciós nyelv (XSD) séma a megadott cél-névtér URI-val a [XmlSchemaSet](../)-ban van-e.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | A séma **targetNamespace** tulajdonsága. |

### Visszatérési érték

**true** ha egy séma a megadott cél-névtér URI-val a [XmlSchemaSet](../)-ban van; egyébként **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) metódus


Megadja, hogy a megadott XML [Schema](../../) definíciós nyelv (XSD) [XmlSchema](../../xmlschema/) objektum a [XmlSchemaSet](../)-ben van-e.

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | A [XmlSchema](../../xmlschema/) objektum. |

### Visszatérési érték

**true** ha a [XmlSchema](../../xmlschema/) objektum a [XmlSchemaSet](../)-ban van; egyébként **false**.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [XmlSchemaSet](../)
* Osztály [XmlSchema](../../xmlschema/)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)