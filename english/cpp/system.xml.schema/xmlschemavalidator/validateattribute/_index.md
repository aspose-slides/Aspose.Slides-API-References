---
title: ValidateAttribute()
second_title: Aspose.Slides for C++ API Reference
description: Validates the attribute name, namespace URI, and value in the current element context.
type: docs
weight: 144
url: /cpp/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\&) method


Validates the attribute name, namespace URI, and value in the current element context.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the attribute to validate. |
| namespaceUri | const [String](../../../system/string/)\& | The namespace URI of the attribute to validate. |
| attributeValue | const [String](../../../system/string/)\& | The value of the attribute to validate. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the attribute. This parameter can be **nullptr**. |

### Return Value

The validated attribute's value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
## XmlSchemaValidator::ValidateAttribute(const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, [XmlValueGetter](../../xmlvaluegetter/), const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\&) method


Validates the attribute name, namespace URI, and value in the current element context.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the attribute to validate. |
| namespaceUri | const [String](../../../system/string/)\& | The namespace URI of the attribute to validate. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | An XmlValueGetter callback used to pass the attribute's value as a type compatible with the XML [Schema](../../) Definition Language (XSD) type of the attribute. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the attribute. This parameter and can be **nullptr**. |

### Return Value

The validated attribute's value.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
