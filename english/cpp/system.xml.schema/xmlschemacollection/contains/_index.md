---
title: Contains()
second_title: Aspose.Slides for C++ API Reference
description: Returns a value indicating whether the targetNamespace of the specified XmlSchema is in the collection.
type: docs
weight: 66
url: /cpp/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) method


Returns a value indicating whether the **targetNamespace** of the specified [XmlSchema](../../xmlschema/) is in the collection.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | The [XmlSchema](../../xmlschema/) object. |

### Return Value

**true** if there is a schema in the collection with the same **targetNamespace**; otherwise, **false**.

## XmlSchemaCollection::Contains(const String\&) method


Returns a value indicating whether a schema with the specified namespace is in the collection.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | The namespace URI associated with the schema. For XML Schemas, this will typically be the target namespace. |

### Return Value

**true** if a schema with the specified namespace is in the collection; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaCollection](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)