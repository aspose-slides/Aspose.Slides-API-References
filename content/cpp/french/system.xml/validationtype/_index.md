---
title: ValidationType
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie le type de validation à effectuer.
type: docs
weight: 729
url: /fr/system.xml/validationtype/
---
## ValidationType énumération

Spécifie le type de validation à effectuer.

```cpp
enum class ValidationType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | 0 | Aucune validation n'est effectuée et aucune erreur de validation n'est levée. Ce paramètre crée un analyseur non validant conforme à XML 1.0. |
| Auto | 1 | Valide si des informations DTD ou de schéma sont trouvées. |
| DTD | 2 | Valide selon le DTD. |
| XDR | 3 | Valide selon les schémas XML-Data Reduced (XDR), y compris les schémas XDR en ligne. Les schémas XDR sont reconnus en utilisant le préfixe d'espace de noms **x-schema** ou la valeur [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/). |
| Schema | 4 | Valide selon le langage de définition XML [Schema](../../system.xml.schema/) (XSD), y compris les schémas XML en ligne. Les schémas XML sont associés aux URI d'espace de noms soit en utilisant l'attribut **schemaLocation**, soit les **Schemas** fournis. |

## Voir aussi

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)