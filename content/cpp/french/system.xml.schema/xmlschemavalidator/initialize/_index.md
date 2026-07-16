---
title: Initialize()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise l'état de l'objet XmlSchemaValidator.
type: docs
weight: 118
url: /fr/system.xml.schema/xmlschemavalidator/initialize/
---
## XmlSchemaValidator::Initialize() méthode

Initialise l'état de l'objet [XmlSchemaValidator](../).

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize()
```

## XmlSchemaValidator::Initialize(const SharedPtr\<XmlSchemaObject\>\&) méthode

Initialise l'état de l'objet [XmlSchemaValidator](../) en utilisant le [XmlSchemaObject](../../xmlschemaobject/) spécifié pour la validation partielle.

```cpp
void System::Xml::Schema::XmlSchemaValidator::Initialize(const SharedPtr<XmlSchemaObject> &partialValidationType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| partialValidationType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | Un [XmlSchemaElement](../../xmlschemaelement/), [XmlSchemaAttribute](../../xmlschemaattribute/) ou [XmlSchemaType](../../xmlschematype/) objet utilisé pour initialiser le contexte de validation de l'objet [XmlSchemaValidator](../) pour une validation partielle. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchemaValidator](../)
* Classe [XmlSchemaObject](../../xmlschemaobject/)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)