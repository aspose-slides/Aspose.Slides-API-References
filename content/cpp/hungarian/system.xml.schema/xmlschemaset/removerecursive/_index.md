---
title: RemoveRecursive()
second_title: Aspose.Slides for C++ API Referenciája
description: Eltávolítja a megadott XML séma definíciós nyelv (XSD) sémát és az összes, általa importált sémát az XmlSchemaSet-ből.
type: docs
weight: 183
url: /hu/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) metódus


Eltávolítja a megadott XML [Schema](../../) (XSD) sémát és az összes, általa importált sémát a [XmlSchemaSet](../)-ból.

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | A [XmlSchema](../../xmlschema/) objektum, amelyet el kell távolítani a [XmlSchemaSet](../)-ból. |

### Visszatérési érték

**true** ha a [XmlSchema](../../xmlschema/) objektum és minden importja sikeresen eltávolításra került; egyébként **false**.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchema](../../xmlschema/)
* Osztály [XmlSchemaSet](../)
* Névtér [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)