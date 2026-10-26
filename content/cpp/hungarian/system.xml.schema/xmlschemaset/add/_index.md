---
title: Add()
second_title: Aspose.Slides C++ API-referencia
description: Hozzáadja a megadott URL-en található XML séma definíciós nyelv (XSD) sémát az XmlSchemaSet-hez.
type: docs
weight: 157
url: /hu/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) method


Hozzáadja a megadott URL-en lévő XML [Schema](../../) definíciós nyelv (XSD) sémát a [XmlSchemaSet](../)-hez.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | A séma **targetNamespace** értéke, vagy **nullptr**, ha a sémában megadott **targetNamespace**-t kell használni. |
| schemaUri | const [String](../../../system/string/)\& | Az URL, amely megadja a betöltendő sémát. |

### Visszatérési érték

Egy [XmlSchema](../../xmlschema/) objektum, ha a séma érvényes. Ha a séma nem érvényes és meg van adva egy ValidationEventHandler, akkor **nullptr** kerül visszaadásra, és a megfelelő validációs esemény kerül kiváltásra. Egyébként XmlSchemaException dobódik.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method


Hozzáadja a [XmlReader](../../../system.xml/xmlreader/)-ban található XML [Schema](../../) definíciós nyelv (XSD) sémát a [XmlSchemaSet](../)-hez.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | A séma **targetNamespace** értéke, vagy **nullptr**, ha a sémában megadott **targetNamespace**-t kell használni. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | A [XmlReader](../../../system.xml/xmlreader/) objektum. |

### Visszatérési érték

Egy [XmlSchema](../../xmlschema/) objektum, ha a séma érvényes. Ha a séma nem érvényes és meg van adva egy ValidationEventHandler, akkor **nullptr** kerül visszaadásra, és a megfelelő validációs esemény kiváltásra kerül. Egyébként XmlSchemaException dobódik.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method


Hozzáadja a megadott [XmlSchemaSet](../)-ben található összes XML [Schema](../../) definíciós nyelv (XSD) sémát a [XmlSchemaSet](../)-hez.

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | A [XmlSchemaSet](../) objektum. |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method


Hozzáadja a megadott [XmlSchema](../../xmlschema/)-t a [XmlSchemaSet](../)-hez.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | A [XmlSchema](../../xmlschema/) objektum, amelyet hozzá kell adni a [XmlSchemaSet](../)-hez. |

### Visszatérési érték

Egy [XmlSchema](../../xmlschema/) objektum, ha a séma érvényes. Ha a séma nem érvényes és meg van adva egy ValidationEventHandler, akkor **nullptr** kerül visszaadásra, és a megfelelő validációs esemény kiváltásra kerül. Egyébként XmlSchemaException dobódik.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchema](../../xmlschema/)
* Osztály [String](../../../system/string/)
* Osztály [XmlSchemaSet](../)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)