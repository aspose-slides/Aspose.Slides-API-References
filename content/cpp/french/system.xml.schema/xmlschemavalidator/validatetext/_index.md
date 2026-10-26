---
title: ValidateText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Valide si la chaîne de texte spécifiée est autorisée dans le contexte de l'élément actuel, et accumule le texte pour la validation si l'élément actuel possède un contenu simple.
type: docs
weight: 183
url: /fr/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) méthode

Valide si le **string** spécifié est autorisé dans le contexte de l'élément actuel, et accumule le texte pour la validation si l'élément actuel possède un contenu simple.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | Un **string** de texte à valider dans le contexte de l'élément actuel. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) méthode

Valide si le texte retourné par l'objet XmlValueGetter spécifié est autorisé dans le contexte de l'élément actuel, et accumule le texte pour la validation si l'élément actuel possède un contenu simple.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | Un rappel XmlValueGetter utilisé pour transmettre la valeur du texte comme un type compatible avec le type du langage de définition XML [Schema](../../) (XSD) de l'attribut. |

## Voir aussi

* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaValidator](../)
* Espace de noms [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)