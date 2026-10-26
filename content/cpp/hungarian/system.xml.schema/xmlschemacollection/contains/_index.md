---
title: Contains()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy értéket, amely jelzi, hogy a megadott XmlSchema targetNamespace-e szerepel-e a gyűjteményben.
type: docs
weight: 66
url: /hu/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Visszaad egy értéket, amely jelzi, hogy a megadott [XmlSchema](../../xmlschema/) **targetNamespace**-e szerepel-e a gyűjteményben.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | A [XmlSchema](../../xmlschema/) objektum. |

### Visszatérési érték

**true** ha a gyűjteményben van olyan séma, amelynek **targetNamespace** megegyezik; egyébként **false**.

## XmlSchemaCollection::Contains(const String\&) method


Visszaad egy értéket, amely jelzi, hogy a megadott névtérrel rendelkező séma szerepel-e a gyűjteményben.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | A sémához társított névtér URI. XML sémák esetén ez általában a cél névtér. |

### Visszatérési érték

**true** ha a megadott névtérrel rendelkező séma a gyűjteményben van; egyébként **false**.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchema](../../xmlschema/)
* Osztály [XmlSchemaCollection](../)
* Osztály [String](../../../system/string/)
* Névtere [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)