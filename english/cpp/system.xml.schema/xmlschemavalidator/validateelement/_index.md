---
title: ValidateElement()
second_title: Aspose.Slides for C++ API Reference
description: Validates the element in the current context.
type: docs
weight: 131
url: /cpp/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) method


Validates the element in the current context.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the element to validate. |
| namespaceUri | const [String](../../../system/string/)\& | The namespace URI of the element to validate. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the element's name. This parameter can be **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) method


Validates the element in the current context with the **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation**, and **xsi:NoNamespaceSchemaLocation** attribute values specified.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | The local name of the element to validate. |
| namespaceUri | const [String](../../../system/string/)\& | The namespace URI of the element to validate. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | An [XmlSchemaInfo](../../xmlschemainfo/) object whose properties are set on successful validation of the element's name. This parameter can be **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | The **xsi:Type** attribute value of the element. This parameter can be **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | The **xsi:Nil** attribute value of the element. This parameter can be **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | The **xsi:SchemaLocation** attribute value of the element. This parameter can be **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | The **xsi:NoNamespaceSchemaLocation** attribute value of the element. This parameter can be **nullptr**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)