---
title: RemoveRecursive()
second_title: Référence API Aspose.Slides pour C++
description: Supprime le schéma XML Schema Definition Language (XSD) spécifié et tous les schémas qu’il importe du XmlSchemaSet.
type: docs
weight: 183
url: /fr/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) méthode


Supprime le schéma XML [Schema](../../) de langage de définition (XSD) spécifié et tous les schémas qu’il importe depuis le [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | L'objet [XmlSchema](../../xmlschema/) à supprimer du [XmlSchemaSet](../). |

### Valeur de retour

**true** si l'objet [XmlSchema](../../xmlschema/) et toutes ses importations ont été supprimés avec succès ; sinon, **false**.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)