---
title: Validate()
second_title: Aspose.Slides pro C++ API Reference
description: "Ověřuje objekt XmlDocument vůči schématům XML Schema Definition Language (XSD), která jsou obsažena v seznamu XmlDocument::get_Schemas."
type: docs
weight: 573
url: /cs/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) metoda

Ověřuje [XmlDocument](../) vůči schématům XML [Schema](../../../system.xml.schema/) Definition Language (XSD), která jsou obsažena v seznamu [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Objekt [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/), který přijímá informace o varováních a chybách ověřování schématu. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) metoda

Ověřuje objekt [XmlNode](../../xmlnode/) uvedený vůči schématům XML [Schema](../../../system.xml.schema/) Definition Language (XSD) v seznamu [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Objekt [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/), který přijímá informace o varováních a chybách ověřování schématu. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Objekt [XmlNode](../../xmlnode/) vytvořený z [XmlDocument](../) pro ověření. |

## Viz také

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlDocument](../)
* Třída [XmlNode](../../xmlnode/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)