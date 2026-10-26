---
title: Remove()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja a megadott XML séma definíciós nyelv (XSD) sémát az XmlSchemaSet-ből.
type: docs
weight: 170
url: /hu/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) metódus

Eltávolítja a megadott XML [Schema](../../) definíciós nyelv (XSD) sémát a [XmlSchemaSet](../)-ból.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | A [XmlSchema](../../xmlschema/) objektum, amelyet a [XmlSchemaSet](../)-ból kell eltávolítani. |

### Visszatérési érték

[XmlSchema](../../xmlschema/) objektum, amelyet a [XmlSchemaSet](../)-ból eltávolítottak, vagy **nullptr**, ha a séma nem található a [XmlSchemaSet](../)-ban.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchema](../../xmlschema/)
* Osztály [XmlSchemaSet](../)
* Névtere [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)