---
title: InferSchema()
second_title: Référence API Aspose.Slides for C++
description: Infère un schéma XML Schema Definition Language (XSD) à partir du document XML contenu dans l'objet XmlReader spécifié.
type: docs
weight: 66
url: /fr/system.xml.schema/xmlschemainference/inferschema/
---
## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&) méthode

Infère un schéma XML [Schema](../../) Definition Language (XSD) à partir du document XML contenu dans l'objet [XmlReader](../../../system.xml/xmlreader/) spécifié.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un objet [XmlReader](../../../system.xml/xmlreader/) contenant le document XML à partir duquel inférer un schéma. |

### Valeur de retour

Un objet [XmlSchemaSet](../../xmlschemaset/) contenant les schémas inférés.

## XmlSchemaInference::InferSchema(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlSchemaSet\>) méthode

Infère un schéma XML [Schema](../../) Definition Language (XSD) à partir du document XML contenu dans l'objet [XmlReader](../../../system.xml/xmlreader/) spécifié, et affine le schéma inféré à l'aide d'un schéma existant dans l'objet [XmlSchemaSet](../../xmlschemaset/) spécifié avec le même espace de noms cible.

```cpp
SharedPtr<XmlSchemaSet> System::Xml::Schema::XmlSchemaInference::InferSchema(const SharedPtr<XmlReader> &instanceDocument, SharedPtr<XmlSchemaSet> schemas)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| instanceDocument | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un objet [XmlReader](../../../system.xml/xmlreader/) contenant le document XML à partir duquel inférer un schéma. |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\> | Un objet [XmlSchemaSet](../../xmlschemaset/) contenant un schéma existant utilisé pour affiner le schéma inféré. |

### Valeur de retour

Un objet [XmlSchemaSet](../../xmlschemaset/) contenant les schémas inférés.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaSet](../../xmlschemaset/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlSchemaInference](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)