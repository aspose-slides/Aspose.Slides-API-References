---
title: idx_get()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne le XmlSchema associé à l'URI d'espace de noms fourni.
type: docs
weight: 53
url: /fr/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) méthode


Retourne le [XmlSchema](../../xmlschema/) associé à l'URI d'espace de noms fourni.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI de l'espace de noms associé au schéma que vous souhaitez retourner. Ce sera généralement le **targetNamespace** du schéma. |

### Valeur de retour

Le [XmlSchema](../../xmlschema/) associé à l'URI d'espace de noms ; **nullptr** s'il n'existe aucun schéma chargé associé à l'espace de noms donné ou si l'espace de noms est associé à un schéma XDR.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaCollection](../)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)