---
title: Add()
second_title: Aspose.Slides for C++ API Reference
description: Adds the XML Schema definition language (XSD) schema at the URL specified to the XmlSchemaSet.
type: docs
weight: 157
url: /system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) method


Adds the XML [Schema](../../) definition language (XSD) schema at the URL specified to the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | The schema **targetNamespace** value, or **nullptr** to use the **targetNamespace** specified in the schema. |
| schemaUri | const [String](../../../system/string/)\& | The URL that specifies the schema to load. |

### Return Value

An [XmlSchema](../../xmlschema/) object if the schema is valid. If the schema is not valid and a ValidationEventHandler is specified, then **nullptr** is returned and the appropriate validation event is raised. Otherwise, an XmlSchemaException is thrown.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) method


Adds the XML [Schema](../../) definition language (XSD) schema contained in the [XmlReader](../../../system.xml/xmlreader/) to the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | The schema **targetNamespace** value, or **nullptr** to use the **targetNamespace** specified in the schema. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | The [XmlReader](../../../system.xml/xmlreader/) object. |

### Return Value

An [XmlSchema](../../xmlschema/) object if the schema is valid. If the schema is not valid and a ValidationEventHandler is specified, then **nullptr** is returned and the appropriate validation event is raised. Otherwise, an XmlSchemaException is thrown.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) method


Adds all the XML [Schema](../../) definition language (XSD) schemas in the given [XmlSchemaSet](../) to the [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | The [XmlSchemaSet](../) object. |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) method


Adds the given [XmlSchema](../../xmlschema/) to the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | The [XmlSchema](../../xmlschema/) object to add to the [XmlSchemaSet](../). |

### Return Value

An [XmlSchema](../../xmlschema/) object if the schema is valid. If the schema is not valid and a ValidationEventHandler is specified, then **nullptr** is returned and the appropriate validation event is raised. Otherwise, an XmlSchemaException is thrown.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaSet](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)