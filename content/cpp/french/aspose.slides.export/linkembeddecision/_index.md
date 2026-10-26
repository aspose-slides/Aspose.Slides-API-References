---
title: LinkEmbedDecision
second_title: Référence API Aspose.Slides pour C++
description: Détermine comment l'objet sera traité lors de l'enregistrement.
type: docs
weight: 911
url: /fr/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision énum

Détermine comment l'objet sera traité lors de l'enregistrement.

```cpp
enum class LinkEmbedDecision
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Link | 0 | L'objet sera stocké à l'extérieur, référencé par URL |
| Embed | 1 | L'objet doit être intégré dans un fichier généré si possible. Si l'intégration est impossible, GetUrl sera appelé et, selon le résultat, l'objet sera référencé par URL ou ignoré. |
| Ignore | 2 | L'objet sera ignoré. |

## Voir aussi

* Espace de noms [Aspose::Slides::Export](../)
* Bibliothèque [Aspose.Slides](../../)