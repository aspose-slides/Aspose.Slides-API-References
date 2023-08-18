---
title: Validate()
second_title: Aspose.Slides for C++ API Reference
description: "Validates the XmlDocument against the XML Schema Definition Language (XSD) schemas contained in the XmlDocument::get_Schemas list."
type: docs
weight: 573
url: /system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) method


Validates the [XmlDocument](../) against the XML [Schema](../../../system.xml.schema/) Definition Language (XSD) schemas contained in the [XmlDocument::get_Schemas](../get_schemas/) list.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | The [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) object that receives information about schema validation warnings and errors. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) method


Validates the [XmlNode](../../xmlnode/) object specified against the XML [Schema](../../../system.xml.schema/) Definition Language (XSD) schemas in the [XmlDocument::get_Schemas](../get_schemas/) list.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | The [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) object that receives information about schema validation warnings and errors. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | The [XmlNode](../../xmlnode/) object created from an [XmlDocument](../) to validate. |

## See Also

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocument](../)
* Class [XmlNode](../../xmlnode/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)