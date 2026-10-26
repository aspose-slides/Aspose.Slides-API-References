---
title: Reprocess()
second_title: Référence API Aspose.Slides pour C++
description: Traite à nouveau un schéma XML Schema definition language (XSD) qui existe déjà dans le XmlSchemaSet.
type: docs
weight: 222
url: /fr/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) méthode


Réprocesses un schéma XML [Schema](../../) definition language (XSD) qui existe déjà dans le [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Le schéma à retraiter. |

### Valeur de retour

Un objet [XmlSchema](../../xmlschema/) si le schéma est un schéma valide. Si le schéma n’est pas valide et qu’un ValidationEventHandler est spécifié, **nullptr** est renvoyé et l’événement de validation approprié est levé. Sinon, une XmlSchemaException est levée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [XmlSchemaSet](../)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)