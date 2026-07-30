---
title: Contains()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Vrací hodnotu, která udává, zda je targetNamespace zadaného XmlSchema ve sbírce.
type: docs
weight: 66
url: /cs/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Vrací hodnotu, která udává, zda **targetNamespace** zadaného [XmlSchema](../../xmlschema/) je ve sbírce.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Objekt [XmlSchema](../../xmlschema/). |

### Návratová hodnota

**true** pokud je ve sbírce schéma se stejným **targetNamespace**; jinak **false**.

## XmlSchemaCollection::Contains(const String\&) method


Vrací hodnotu, která udává, zda je ve sbírce schéma se zadaným jmenným prostorem.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru spojeného se schématem. Pro XML Schema to bude typicky cílový jmenný prostor. |

### Návratová hodnota

**true** pokud je ve sbírce schéma se zadaným jmenným prostorem; jinak **false**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlSchema](../../xmlschema/)
* Třída [XmlSchemaCollection](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)