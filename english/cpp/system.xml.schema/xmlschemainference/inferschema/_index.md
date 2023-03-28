---
title: InferSchema()
second_title: Aspose.Slides for C++ API Reference
description: Infers an XML Schema Definition Language (XSD) schema from the XML document contained in the XmlReader object specified.
type: docs
weight: 66
url: /cpp/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\&) method


Infers an XML [Schema](../../) Definition Language (XSD) schema from the XML document contained in the [XmlReader](../../../system.xml/xmlreader/) object specified.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | An [XmlReader](../../../system.xml/xmlreader/) object containing the XML document to infer a schema from. |

### Return Value

An [XmlSchemaSet](../../xmlschemaset/) object containing the inferred schemas.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
## XmlSchemaInference::InferSchema(const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\&, [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>) method


Infers an XML [Schema](../../) Definition Language (XSD) schema from the XML document contained in the [XmlReader](../../../system.xml/xmlreader/) object specified, and refines the inferred schema using an existing schema in the [XmlSchemaSet](../../xmlschemaset/) object specified with the same target namespace.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | An [XmlReader](../../../system.xml/xmlreader/) object containing the XML document to infer a schema from. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | An [XmlSchemaSet](../../xmlschemaset/) object containing an existing schema used to refine the inferred schema. |

### Return Value

An [XmlSchemaSet](../../xmlschemaset/) object containing the inferred schemas.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
