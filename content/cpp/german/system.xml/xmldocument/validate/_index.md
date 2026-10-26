---
title: Validate()
second_title: Aspose.Slides für C++ API-Referenz
description: "Validiert das XmlDocument gegen die XML Schema Definition Language (XSD)-Schemata, die in der XmlDocument::get_Schemas-Liste enthalten sind."
type: docs
weight: 573
url: /de/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) Methode

Validiert das [XmlDocument](../) gegen die XML [Schema](../../../system.xml.schema/) Definition Language (XSD)-Schemata, die in der [XmlDocument::get_Schemas](../get_schemas/)-Liste enthalten sind.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Das [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)-Objekt, das Informationen über Warnungen und Fehler bei der Schema-Validierung empfängt. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) Methode

Validiert das angegebene [XmlNode](../../xmlnode/)-Objekt gegen die XML [Schema](../../../system.xml.schema/) Definition Language (XSD)-Schemata in der [XmlDocument::get_Schemas](../get_schemas/)-Liste.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Das [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)-Objekt, das Informationen über Warnungen und Fehler bei der Schema-Validierung empfängt. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Das [XmlNode](../../xmlnode/)-Objekt, das aus einem [XmlDocument](../) zur Validierung erstellt wurde. |

## Siehe auch

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlDocument](../)
* Klasse [XmlNode](../../xmlnode/)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)