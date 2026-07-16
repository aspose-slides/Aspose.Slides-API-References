---
title: Contains()
second_title: Référence de l'API Aspose.Slides for C++
description: Indique si un schéma XML Schema definition language (XSD) avec l'URI d'espace de noms cible spécifié se trouve dans le XmlSchemaSet.
type: docs
weight: 196
url: /fr/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) méthode

Indique si un schéma XML [Schema](../../) langage de définition (XSD) avec l'URI d'espace de noms cible spécifié se trouve dans le [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | La propriété **targetNamespace** du schéma. |

### Valeur de retour

**true** si un schéma avec l'URI d'espace de noms cible spécifié se trouve dans le [XmlSchemaSet](../) ; sinon, **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) méthode

Indique si l'objet [XmlSchema](../../xmlschema/) XML [Schema](../../) langage de définition (XSD) spécifié se trouve dans le [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | L'objet [XmlSchema](../../xmlschema/). |

### Valeur de retour

**true** si l'objet [XmlSchema](../../xmlschema/) se trouve dans le [XmlSchemaSet](../) ; sinon, **false**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaSet](../)
* Classe [XmlSchema](../../xmlschema/)
* Espace de noms [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)