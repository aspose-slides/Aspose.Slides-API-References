---
title: Validate()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: "Waliduje XmlDocument względem schematów XML Schema Definition Language (XSD) zawartych na liście XmlDocument::get_Schemas."
type: docs
weight: 573
url: /pl/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) metoda


Waliduje [XmlDocument](../) względem schematów XML [Schema](../../../system.xml.schema/) Definition Language (XSD) zawartych w liście [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) obiekt, który odbiera informacje o ostrzeżeniach i błędach walidacji schematu. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) metoda


Waliduje określony obiekt [XmlNode](../../xmlnode/) względem schematów XML [Schema](../../../system.xml.schema/) Definition Language (XSD) znajdujących się na liście [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) obiekt, który odbiera informacje o ostrzeżeniach i błędach walidacji schematu. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/) obiekt utworzony z [XmlDocument](../) w celu walidacji. |

## Zobacz także

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlDocument](../)
* Klasa [XmlNode](../../xmlnode/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)