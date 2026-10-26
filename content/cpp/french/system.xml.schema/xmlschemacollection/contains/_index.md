---
title: Contains()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une valeur indiquant si le targetNamespace du XmlSchema spécifié se trouve dans la collection.
type: docs
weight: 66
url: /fr/system.xml.schema/xmlschemacollection/contains/
---
## XmlSchemaCollection::Contains(const SharedPtr\<XmlSchema\>\&) méthode


Renvoie une valeur indiquant si le **targetNamespace** du [XmlSchema](../../xmlschema/) spécifié se trouve dans la collection.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | L'objet [XmlSchema](../../xmlschema/). |

### Valeur de retour

**true** si un schéma de la collection possède le même **targetNamespace** ; sinon, **false**.

## XmlSchemaCollection::Contains(const String\&) méthode


Renvoie une valeur indiquant si un schéma avec l'espace de noms spécifié se trouve dans la collection.

```cpp
bool System::Xml::Schema::XmlSchemaCollection::Contains(const String &ns)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI d'espace de noms associé au schéma. Pour les schémas XML, il s'agit généralement de l'espace de noms cible. |

### Valeur de retour

**true** si un schéma avec l'espace de noms spécifié se trouve dans la collection ; sinon, **false**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaCollection](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)