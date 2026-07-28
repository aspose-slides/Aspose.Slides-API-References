---
title: InferSchema()
second_title: Aspose.Slides for C++ API referencia
description: Megállapít egy XML Schema Definition Language (XSD) sémát a megadott XmlReader objektumban található XML dokumentumból.
type: docs
weight: 66
url: /hu/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) módszer

Megállapít egy XML [Schema](../../) Definíciós Nyelv (XSD) sémát a megadott [XmlReader](../../../system.xml/xmlreader/) objektumban található XML dokumentumból.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/) objektum, amely az XML dokumentumot tartalmazza, amelyből a sémát meg kell állapítani. |

### Visszatérési érték

Egy [XmlSchemaSet](../../xmlschemaset/) objektum, amely a meghatározott sémákat tartalmazza.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) módszer

Megállapít egy XML [Schema](../../) Definíciós Nyelv (XSD) sémát a megadott [XmlReader](../../../system.xml/xmlreader/) objektumban található XML dokumentumból, és finomítja a meghatározott sémát egy meglévő sémával, amely a megadott [XmlSchemaSet](../../xmlschemaset/) objektumban található, azonos cél névtérrel.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Egy [XmlReader](../../../system.xml/xmlreader/) objektum, amely az XML dokumentumot tartalmazza, amelyből a sémát meg kell állapítani. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Egy [XmlSchemaSet](../../xmlschemaset/) objektum, amely egy meglévő sémát tartalmaz, amelyet a meghatározott séma finomításához használnak. |

### Visszatérési érték

Egy [XmlSchemaSet](../../xmlschemaset/) objektum, amely a meghatározott sémákat tartalmazza.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchemaSet](../../xmlschemaset/)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Osztály [XmlSchemaInference](../)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)