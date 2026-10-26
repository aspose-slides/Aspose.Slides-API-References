---
title: Compile()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compile le modèle XML SchemaObject (SOM) en informations de schéma pour la validation. Utilisé pour vérifier la structure syntaxique et sémantique du SOM construit programmétiquement. La vérification de validation sémantique est effectuée lors de la compilation.
type: docs
weight: 352
url: /fr/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) méthode

Compile le modèle XML [Schema](../../)[Object](../../../system/object/) (SOM) en informations de schéma pour la validation. Utilisé pour vérifier la structure syntaxique et sémantique du SOM construit programmétiquement. La vérification de validation sémantique est effectuée pendant la compilation.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Le gestionnaire d'événements de validation qui reçoit des informations sur les erreurs de validation XML [Schema](../../). |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) méthode

Compile le modèle XML [Schema](../../)[Object](../../../system/object/) (SOM) en informations de schéma pour la validation. Utilisé pour vérifier la structure syntaxique et sémantique du SOM construit programmétiquement. La vérification de validation sémantique est effectuée pendant la compilation.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Le gestionnaire d'événements de validation qui reçoit des informations sur les erreurs de validation XML [Schema](../../). |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre les espaces de noms référencés dans les éléments **include** et **import**. |

## Voir aussi

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [XmlSchema](../)
* classe [XmlResolver](../../../system.xml/xmlresolver/)
* espace de noms [System::Xml::Schema](../../)
* bibliothèque [Aspose.Slides](../../../)