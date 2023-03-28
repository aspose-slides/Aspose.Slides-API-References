---
title: CheckValidity()
second_title: Aspose.Slides for C++ API Reference
description: Verifies that the XML data in the XPathNavigator conforms to the XML Schema definition language (XSD) schema provided.
type: docs
weight: 755
url: /cpp/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity([SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)) method


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
