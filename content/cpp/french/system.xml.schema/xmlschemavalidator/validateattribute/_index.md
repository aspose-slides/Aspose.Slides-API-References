---
title: ValidateAttribute()
second_title: Référence de l'API Aspose.Slides pour C++
description: Valide le nom de l'attribut, l'URI d'espace de noms et la valeur dans le contexte de l'élément actuel.
type: docs
weight: 144
url: /fr/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) méthode

Valide le nom de l’attribut, l’URI de l’espace de noms et la valeur dans le contexte de l’élément actuel.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l’attribut à valider. |
| namespaceUri | const [String](../../../system/string/)\& | L’URI de l’espace de noms de l’attribut à valider. |
| attributeValue | const [String](../../../system/string/)\& | La valeur de l’attribut à valider. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objet [XmlSchemaInfo](../../xmlschemainfo/) dont les propriétés sont définies après une validation réussie de l’attribut. Ce paramètre peut être **nullptr**. |

### Valeur de retour

La valeur de l’attribut validé.

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) méthode

Valide le nom de l’attribut, l’URI de l’espace de noms et la valeur dans le contexte de l’élément actuel.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l’attribut à valider. |
| namespaceUri | const [String](../../../system/string/)\& | L’URI de l’espace de noms de l’attribut à valider. |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | Un rappel XmlValueGetter utilisé pour transmettre la valeur de l’attribut sous un type compatible avec le langage de définition XML [Schema](../../) (XSD) de l’attribut. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objet [XmlSchemaInfo](../../xmlschemainfo/) dont les propriétés sont définies après une validation réussie de l’attribut. Ce paramètre peut être **nullptr**. |

### Valeur de retour

La valeur de l’attribut validé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaInfo](../../xmlschemainfo/)
* Classe [XmlSchemaValidator](../)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)