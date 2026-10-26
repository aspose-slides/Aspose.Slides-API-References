---
title: Validate()
second_title: Aspose.Slides voor C++ API-referentie
description: "Valideert het XmlDocument tegen de XML Schema Definition Language (XSD) schema's die in de XmlDocument::get_Schemas lijst staan."
type: docs
weight: 573
url: /nl/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) methode

Valideert de [XmlDocument](../) tegen de XML [Schema](../../../system.xml.schema/) Definition Language (XSD) schema's die in de [XmlDocument::get_Schemas](../get_schemas/) lijst staan.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Het [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) object dat informatie ontvangt over waarschuwingen en fouten bij schemavalidatie. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) methode

Valideert het opgegeven [XmlNode](../../xmlnode/) object tegen de XML [Schema](../../../system.xml.schema/) Definition Language (XSD) schema's in de [XmlDocument::get_Schemas](../get_schemas/) lijst.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Het [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) object dat informatie ontvangt over waarschuwingen en fouten bij schemavalidatie. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Het [XmlNode](../../xmlnode/) object dat is gemaakt van een [XmlDocument](../) om te valideren. |

## Zie ook

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlDocument](../)
* Klasse [XmlNode](../../xmlnode/)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)