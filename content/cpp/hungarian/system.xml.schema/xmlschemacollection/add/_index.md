---
title: Add()
second_title: Aspose.Slides for C++ API referenciája
description: A megadott URL által megadott sémát a séma gyűjteményhez adja hozzá.
type: docs
weight: 40
url: /hu/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) metódus


A megadott URL által meghatározott sémát hozzáadja a séma gyűjteményhez.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | A sémához kapcsolódó névtér URI. Az XML sémáknál ez általában a **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | Az URL, amely meghatározza a betöltendő sémát. |

### Visszatérési érték

A [XmlSchema](../../xmlschema/) amely a séma gyűjteményhez lett hozzáadva; **nullptr**, ha a hozzáadott séma XDR séma vagy ha a sémában fordítási hibák vannak.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) metódus


A [XmlReader](../../../system.xml/xmlreader/)-ban található sémát hozzáadja a séma gyűjteményhez.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | A sémához kapcsolódó névtér URI. Az XML sémáknál ez általában a **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) tartalmazza a hozzáadandó sémát. |

### Visszatérési érték

A [XmlSchema](../../xmlschema/) a séma gyűjteményhez lett hozzáadva; **nullptr**, ha a hozzáadott séma XDR séma vagy ha a sémában fordítási hibák vannak.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metódus


A [XmlReader](../../../system.xml/xmlreader/)-ban található sémát hozzáadja a séma gyűjteményhez. A megadott [XmlResolver](../../../system.xml/xmlresolver/) a külső erőforrások feloldására szolgál.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | A sémához kapcsolódó névtér URI. Az XML sémáknál ez általában a **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) tartalmazza a hozzáadandó sémát. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a **include** és **import** elemekben vagy **x-schema** attribútumban hivatkozott névterek feloldására szolgál (XDR sémák). Ha **nullptr**, a külső hivatkozások nincsenek feloldva. |

### Visszatérési érték

A [XmlSchema](../../xmlschema/) a séma gyűjteményhez lett hozzáadva; **nullptr**, ha a hozzáadott séma XDR séma vagy ha a sémában fordítási hibák vannak.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) metódus


A [XmlSchema](../../xmlschema/)-t hozzáadja a gyűjteményhez.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | A [XmlSchema](../../xmlschema/) a gyűjteményhez adandó. |

### Visszatérési érték

A [XmlSchema](../../xmlschema/) objektum.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metódus


A [XmlSchema](../../xmlschema/)-t hozzáadja a gyűjteményhez. A megadott [XmlResolver](../../../system.xml/xmlresolver/) a külső hivatkozások feloldására szolgál.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | A [XmlSchema](../../xmlschema/) a gyűjteményhez adandó. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | A [XmlResolver](../../../system.xml/xmlresolver/) a **include** és **import** elemekben hivatkozott névterek feloldására szolgál. Ha **nullptr**, a külső hivatkozások nincsenek feloldva. |

### Visszatérési érték

A [XmlSchema](../../xmlschema/) a séma gyűjteményhez lett hozzáadva.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) metódus


A megadott gyűjteményben definiált összes névteret (az azokhoz tartozó sémákkal együtt) hozzáadja ehhez a gyűjteményhez.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | A [XmlSchemaCollection](../) amelyet hozzá szeretne adni ehhez a gyűjteményhez. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlSchema](../../xmlschema/)
* Osztály [String](../../../system/string/)
* Osztály [XmlSchemaCollection](../)
* Osztály [XmlReader](../../../system.xml/xmlreader/)
* Osztály [XmlResolver](../../../system.xml/xmlresolver/)
* Névtér [System::Xml::Schema](../../)
* Könyvtár [Aspose.Slides](../../../)