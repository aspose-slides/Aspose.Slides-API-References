---
title: XmlSchemaContentProcessing
second_title: Référence de l'API Aspose.Slides pour C++
description: Fournit des informations sur le mode de validation des remplacements d'éléments any et anyAttribute.
type: docs
weight: 976
url: /fr/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing énum

Fournit des informations sur le mode de validation des remplacements d'éléments **any** et **anyAttribute**.

```cpp
enum class XmlSchemaContentProcessing
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Les éléments du document ne sont pas validés. |
| Skip | 1 | Les éléments du document doivent être du XML bien formé et ne sont pas validés par le schéma. |
| Lax | 2 | Si le schéma associé est trouvé, les éléments du document seront validés. Aucune erreur ne sera levée sinon. |
| Strict | 3 | Le processeur de schéma doit trouver un schéma associé à l’espace de noms indiqué pour valider les éléments du document. |

## Voir aussi

* Espace de noms [System::Xml::Schema](../)
* Bibliothèque [Aspose.Slides](../../)