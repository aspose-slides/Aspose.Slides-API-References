---
title: ValidateWhitespace()
second_title: Référence API Aspose.Slides pour C++
description: Valide si les espaces blancs dans la chaîne spécifiée sont autorisés dans le contexte de l'élément actuel, et accumule les espaces blancs pour la validation si l'élément actuel possède un contenu simple.
type: docs
weight: 196
url: /fr/system.xml.schema/xmlschemavalidator/validatewhitespace/
---
## XmlSchemaValidator::ValidateWhitespace(const String\&) method


Vérifie si les espaces blancs dans la **string** spécifiée sont autorisés dans le contexte de l'élément actuel, et accumule les espaces blancs pour la validation si l'élément actuel possède un contenu simple.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(const String &elementValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Un **string** d'espaces blancs à valider dans le contexte de l'élément actuel. |

## XmlSchemaValidator::ValidateWhitespace(XmlValueGetter) method


Vérifie si les espaces blancs retournés par l'objet XmlValueGetter spécifié sont autorisés dans le contexte de l'élément actuel, et accumule les espaces blancs pour la validation si l'élément actuel possède un contenu simple.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateWhitespace(XmlValueGetter elementValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Un rappel XmlValueGetter utilisé pour transmettre la valeur des espaces blancs sous un type compatible avec le type du langage de définition XML [Schema](../../) (XSD) de l'attribut. |

## Voir aussi

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Class [String](../../../system/string/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)