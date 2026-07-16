---
title: Schemas()
second_title: Aspose.Slides pour C++ - Référence de l'API
description: Retourne une collection de tous les schémas du langage de définition XML Schema (XSD) dans le XmlSchemaSet.
type: docs
weight: 248
url: /fr/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() méthode

Retourne une collection de tous les schémas XML [Schema](../../) langage de définition (XSD) dans le [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### Valeur de retour

Un objet IList contenant tous les schémas qui ont été ajoutés au [XmlSchemaSet](../). Si aucun schéma n’a été ajouté au [XmlSchemaSet](../), une collection vide est retournée.

## XmlSchemaSet::Schemas(String) méthode

Retourne une collection de tous les schémas XML [Schema](../../) langage de définition (XSD) dans le [XmlSchemaSet](../) qui appartiennent à l’espace de noms fourni.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | La propriété **targetNamespace** du schéma. |

### Valeur de retour

Un objet IList contenant tous les schémas qui ont été ajoutés au [XmlSchemaSet](../) qui appartiennent à l’espace de noms fourni. Si aucun schéma n’a été ajouté au [XmlSchemaSet](../), une collection vide est retournée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IList](../../../system.collections.generic/ilist/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* Classe [List](../../../system.collections.generic/list/)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)