---
title: XmlOutputMethod
second_title: Référence de l'API Aspose.Slides pour C++
description: Spécifie la méthode utilisée pour sérialiser la sortie XmlWriter.
type: docs
weight: 846
url: /fr/system.xml/xmloutputmethod/
---
## XmlOutputMethod enum

Spécifie la méthode utilisée pour sérialiser la sortie [XmlWriter](../xmlwriter/).

```cpp
enum class XmlOutputMethod
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Xml | 0 | Sérialiser selon les règles XML 1.0. |
| Html | 1 | Sérialiser selon les règles HTML spécifiées par XSLT. |
| Text | 2 | Sérialiser uniquement les blocs de texte. |
| AutoDetect | 3 | Utiliser les règles XSLT pour choisir entre les méthodes de sortie [XmlOutputMethod::Xml](./) et [XmlOutputMethod::Html](./) au moment de l'exécution. |

## Voir aussi

* Espace de noms [System::Xml](../)
* Bibliothèque [Aspose.Slides](../../)