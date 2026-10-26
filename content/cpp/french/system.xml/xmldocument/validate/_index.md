---
title: Validate()
second_title: Aspose.Slides pour C++ Référence de l'API
description: "Valide le XmlDocument par rapport aux schémas XML Schema Definition Language (XSD) contenus dans la liste XmlDocument::get_Schemas."
type: docs
weight: 573
url: /fr/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) méthode

Valide le [XmlDocument](../) à l'aide des schémas XML [Schema](../../../system.xml.schema/) Definition Language (XSD) contenus dans la liste [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | L'objet [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) qui reçoit les informations sur les avertissements et les erreurs de validation de schéma. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) méthode

Valide l'objet [XmlNode](../../xmlnode/) spécifié à l'aide des schémas XML [Schema](../../../system.xml.schema/) Definition Language (XSD) dans la liste [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | L'objet [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) qui reçoit les informations sur les avertissements et les erreurs de validation de schéma. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | L'objet [XmlNode](../../xmlnode/) créé à partir d'un [XmlDocument](../) à valider. |

## Voir aussi

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlDocument](../)
* Classe [XmlNode](../../xmlnode/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)