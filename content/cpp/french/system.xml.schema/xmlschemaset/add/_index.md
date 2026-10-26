---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute le schéma du langage de définition XML (XSD) à l'URL spécifiée au XmlSchemaSet.
type: docs
weight: 157
url: /fr/system.xml.schema/xmlschemaset/add/
---
## XmlSchemaSet::Add(String, const String\&) méthode

Ajoute le schéma du langage de définition XML [Schema](../../) (XSD) à l'URL spécifiée au [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const String &schemaUri)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | La valeur **targetNamespace** du schéma, ou **nullptr** pour utiliser le **targetNamespace** spécifié dans le schéma. |
| schemaUri | const [String](../../../system/string/)\& | L'URL qui indique le schéma à charger. |

### Valeur de retour

Un objet [XmlSchema](../../xmlschema/) si le schéma est valide. Si le schéma n'est pas valide et qu'un ValidationEventHandler est spécifié, alors **nullptr** est renvoyé et l'événement de validation approprié est déclenché. Sinon, une XmlSchemaException est levée.

## XmlSchemaSet::Add(String, const SharedPtr\<XmlReader\>\&) méthode

Ajoute le schéma du langage de définition XML [Schema](../../) (XSD) contenu dans le [XmlReader](../../../system.xml/xmlreader/) au [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(String targetNamespace, const SharedPtr<XmlReader> &schemaDocument)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | La valeur **targetNamespace** du schéma, ou **nullptr** pour utiliser le **targetNamespace** spécifié dans le schéma. |
| schemaDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | L'objet [XmlReader](../../../system.xml/xmlreader/). |

### Valeur de retour

Un objet [XmlSchema](../../xmlschema/) si le schéma est valide. Si le schéma n'est pas valide et qu'un ValidationEventHandler est spécifié, alors **nullptr** est renvoyé et l'événement de validation approprié est déclenché. Sinon, une XmlSchemaException est levée.

## XmlSchemaSet::Add(const SharedPtr\<XmlSchemaSet\>\&) méthode

Ajoute tous les schémas du langage de définition XML [Schema](../../) (XSD) dans le [XmlSchemaSet](../) donné au [XmlSchemaSet](../).

```cpp
void System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchemaSet> &schemas)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../)\>\& | L'objet [XmlSchemaSet](../). |

## XmlSchemaSet::Add(const SharedPtr\<XmlSchema\>\&) méthode

Ajoute le [XmlSchema](../../xmlschema/) donné au [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Add(const SharedPtr<XmlSchema> &schema)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | L'objet [XmlSchema](../../xmlschema/) à ajouter au [XmlSchemaSet](../). |

### Valeur de retour

Un objet [XmlSchema](../../xmlschema/) si le schéma est valide. Si le schéma n'est pas valide et qu'un ValidationEventHandler est spécifié, alors **nullptr** est renvoyé et l'événement de validation approprié est déclenché. Sinon, une XmlSchemaException est levée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaSet](../)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)