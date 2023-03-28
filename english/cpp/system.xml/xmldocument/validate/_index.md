---
title: Validate()
second_title: Aspose.Slides for C++ API Reference
description: "Validates the XmlDocument against the XML Schema Definition Language (XSD) schemas contained in the XmlDocument::get_Schemas list."
type: docs
weight: 573
url: /cpp/system.xml/xmldocument/validate/
---
## XmlDocument::Validate([Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)) method


Validates the [XmlDocument](../) against the XML [Schema](../../../system.xml.schema/) Definition Language (XSD) schemas contained in the [XmlDocument::get_Schemas](../get_schemas/) list.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | The [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) object that receives information about schema validation warnings and errors. |

## See Also

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlDocument::Validate([Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/), const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\&) method


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
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
