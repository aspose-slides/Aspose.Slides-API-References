---
title: GetUnspecifiedDefaultAttributes()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Valide les contraintes d'identité sur les attributs par défaut et remplit la List spécifiée avec des objets XmlSchemaAttribute pour tous les attributs ayant des valeurs par défaut qui n'ont pas été préalablement validés à l'aide de la méthode XmlSchemaValidator::ValidateAttribute dans le contexte de l'élément."
type: docs
weight: 157
url: /fr/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) méthode

Valide les contraintes d'identité sur les attributs par défaut et remplit la List spécifiée avec des objets [XmlSchemaAttribute](../../xmlschemaattribute/) pour tous les attributs ayant des valeurs par défaut qui n'ont pas encore été validés à l'aide de la méthode [XmlSchemaValidator::ValidateAttribute](../validateattribute/) dans le contexte de l'élément.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | Une List à remplir avec des objets [XmlSchemaAttribute](../../xmlschemaattribute/) pour tous les attributs qui n'ont pas encore été rencontrés lors de la validation dans le contexte de l'élément. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [List](../../../system.collections.generic/list/)
* Classe [Object](../../../system/object/)
* Classe [XmlSchemaValidator](../)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)