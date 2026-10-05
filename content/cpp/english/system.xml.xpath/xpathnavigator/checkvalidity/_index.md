---
title: CheckValidity()
second_title: Aspose.Slides for C++ API Reference
description: Verifies that the XML data in the XPathNavigator conforms to the XML Schema definition language (XSD) schema provided.
type: docs
weight: 755
url: /system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) method


Verifies that the XML data in the [XPathNavigator](../) conforms to the XML [Schema](../../../system.xml.schema/) definition language (XSD) schema provided.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | The XmlSchemaSet containing the schemas used to validate the XML data contained in the [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | The ValidationEventHandler that receives information about schema validation warnings and errors. |

### Return Value

**true** if no schema validation errors occurred; otherwise, **false**.

### Exceptions

| Exception | Description |
| --- | --- |
| XmlSchemaValidationException | A schema validation error occurred, and no ValidationEventHandler was specified to handle validation errors. |
| InvalidOperationException | The [XPathNavigator](../) is positioned on a node that is not an element, attribute, or the root node or there is not type information to perform validation. |
| ArgumentException | The method was called with an XmlSchemaSet parameter when the [XPathNavigator](../) was not positioned on the root node of the XML data. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)