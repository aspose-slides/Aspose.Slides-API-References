---
title: idx_get()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a megadott névtér URI-hez tartozó XmlSchema-t.
type: docs
weight: 53
url: /hu/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) metódus


Visszaadja a [XmlSchema](../../xmlschema/) értéket, amely a megadott névtér URI-hez tartozik.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | A névtér URI, amely a visszaadni kívánt sémahoz kapcsolódik. Ez általában a séma **targetNamespace** értéke. |

### Visszatérési érték

A névtér URI-hez kapcsolódó [XmlSchema](../../xmlschema/); **nullptr**, ha nincs betöltött séma a megadott névtérhez kapcsolódva, vagy ha a névtér egy XDR sémához kapcsolódik.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchema](../../xmlschema/)
* Osztály [String](../../../system/string/)
* Osztály [XmlSchemaCollection](../)
* Névtere [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)