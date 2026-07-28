---
title: Reprocess()
second_title: Aspose.Slides C++ API referenciája
description: Újrafeldolgozza a XmlSchemaSet-ben már meglévő XML Schema definíciós nyelv (XSD) sémát.
type: docs
weight: 222
url: /hu/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) metódus

Reprocesses an XML [Schema](../../) definition language (XSD) schema that already exists in the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Az újrafeldolgozandó séma. |

### Visszatérési érték

Egy [XmlSchema](../../xmlschema/) objektum, ha a séma érvényes. Ha a séma nem érvényes, és egy ValidationEventHandler van megadva, akkor **nullptr** kerül visszaadásra, és a megfelelő validációs esemény kerül kiváltásra. Egyébként XmlSchemaException kerül dobásra.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchema](../../xmlschema/)
* Osztály [XmlSchemaSet](../)
* Névtér [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)