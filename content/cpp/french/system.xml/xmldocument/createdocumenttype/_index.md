---
title: CreateDocumentType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un nouvel objet XmlDocumentType.
type: docs
weight: 313
url: /fr/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method

Renvoie un nouvel objet [XmlDocumentType](../../xmldocumenttype/).

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nom du type de document. |
| publicId | const [String](../../../system/string/)\& | Identifiant public du type de document ou **nullptr**. Vous pouvez spécifier un URI public ainsi qu'un identifiant système pour identifier l'emplacement du sous-ensemble DTD externe. |
| systemId | const [String](../../../system/string/)\& | Identifiant système du type de document ou **nullptr**. Spécifie l'URL de l'emplacement du fichier pour le sous-ensemble DTD externe. |
| internalSubset | const [String](../../../system/string/)\& | Sous-ensemble interne DTD du type de document ou **nullptr**. |

### Valeur de retour

Le nouveau [XmlDocumentType](../../xmldocumenttype/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)