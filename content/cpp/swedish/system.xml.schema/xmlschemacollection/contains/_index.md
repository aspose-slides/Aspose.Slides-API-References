---
title: Contains()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett värde som indikerar om targetNamespace för den angivna XmlSchema finns i samlingen.
type: docs
weight: 66
url: /sv/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) metod


Returnerar ett värde som indikerar om **targetNamespace** för den angivna [XmlSchema](../../xmlschema/) finns i samlingen.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Objektet [XmlSchema](../../xmlschema/). |

### Returvärde

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## XmlSchemaCollection::Contains(const String\&) metod


Returnerar ett värde som indikerar om ett schema med den angivna namnrymden finns i samlingen.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Namnutrymms-URI som är kopplad till schemat. För XML-scheman är detta vanligtvis målnamnutrymmet. |

### Returvärde

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchema](../../xmlschema/)
* Klass [XmlSchemaCollection](../)
* Klass [String](../../../system/string/)
* Namnutrymme [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)