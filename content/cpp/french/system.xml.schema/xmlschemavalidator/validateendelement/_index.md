---
title: ValidateEndElement()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vérifie si le contenu texte de l'élément est valide selon son type de données pour les éléments à contenu simple, et vérifie si le contenu de l'élément actuel est complet pour les éléments à contenu complexe.
type: docs
weight: 209
url: /fr/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) méthode

Vérifie si le contenu texte de l'élément est valide selon son type de données pour les éléments à contenu simple, et vérifie si le contenu de l'élément actuel est complet pour les éléments à contenu complexe.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objet [XmlSchemaInfo](../../xmlschemainfo/) dont les propriétés sont définies lors de la validation réussie de l'élément. Ce paramètre peut être **nullptr**. |

### Valeur de retour

La valeur texte analysée et typée de l'élément si l'élément possède un contenu simple.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) méthode

Vérifie si le contenu texte de l'élément spécifié est valide selon son type de données.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objet [XmlSchemaInfo](../../xmlschemainfo/) dont les propriétés sont définies lors de la validation réussie du contenu texte de l'élément. Ce paramètre peut être **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Le contenu texte typé de l'élément. |

### Valeur de retour

Le contenu simple analysé et typé de l'élément.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [XmlSchemaInfo](../../xmlschemainfo/)
* Classe [XmlSchemaValidator](../)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)