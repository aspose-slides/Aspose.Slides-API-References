---
title: ValidateEndElement()
second_title: Aspose.Slides for C++ API Reference
description: Verifies if the text content of the element is valid according to its data type for elements with simple content, and verifies if the content of the current element is complete for elements with complex content.
type: docs
weight: 209
url: /system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method


Verifies if the text content of the element is valid according to its data type for elements with simple content, and verifies if the content of the current element is complete for elements with complex content.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the element. This parameter can be **nullptr**. |

### Return Value

The parsed, typed text value of the element if the element has simple content.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method


Verifies if the text content of the element specified is valid according to its data type.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the text content of the element. This parameter can be **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | The typed text content of the element. |

### Return Value

The parsed, typed simple content of the element.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)