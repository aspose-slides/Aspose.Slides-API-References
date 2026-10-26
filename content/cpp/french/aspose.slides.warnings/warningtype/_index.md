---
title: WarningType
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un type d'avertissement.
type: docs
weight: 92
url: /fr/aspose.slides.warnings/warningtype/
---
## WarningType enum


Représente un type d'avertissement.

```cpp
enum class WarningType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| SourceFileCorruption | 0 | Un problème a été détecté dans le document source, ce qui rend très probable que le document ne pourra pas être ouvert s'il est enregistré dans son format d'origine. |
| DataLoss | 1 | Le texte, le graphique, l'image ou d'autres données seront complètement manquants soit dans l'arbre du document après le chargement, soit dans le document créé après l'enregistrement. |
| MajorFormattingLoss | 2 | Perte de mise en forme majeure. |
| MinorFormattingLoss | 3 | Perte de mise en forme mineure. |
| CompatibilityIssue | 4 | Il s'agit d'un problème connu qui empêchera le document d'être ouvert par certains agents utilisateur, ou par des versions antérieures d'agents utilisateur. |
| UnexpectedContent | 99 | Certain contenu du document source n'a pas pu être reconnu (c'est-à-dire qu'il n'est pas pris en charge), cela peut ou non causer des problèmes ou entraîner une perte de données/de mise en forme. |

## Voir également

* Espace de noms [Aspose::Slides::Warnings](../)
* Bibliothèque [Aspose.Slides](../../)