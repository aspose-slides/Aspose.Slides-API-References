---
title: Validate()
second_title: Aspose.Slides för C++ API-referens
description: "Validerar XmlDocument mot XML Schema Definition Language (XSD)-scheman som finns i listan XmlDocument::get_Schemas."
type: docs
weight: 573
url: /sv/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) metod

Validerar [XmlDocument](../) mot XML [Schema](../../../system.xml.schema/) Definition Language (XSD) scheman i listan [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Objektet [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) som tar emot information om varningar och fel vid schemavalidering. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) metod

Validerar det specificerade [XmlNode](../../xmlnode/)-objektet mot XML [Schema](../../../system.xml.schema/) Definition Language (XSD) scheman i listan [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Objektet [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) som tar emot information om varningar och fel vid schemavalidering. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Objektet [XmlNode](../../xmlnode/) som skapats från en [XmlDocument](../) för att validera. |

## Se även

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocument](../)
* Class [XmlNode](../../xmlnode/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)