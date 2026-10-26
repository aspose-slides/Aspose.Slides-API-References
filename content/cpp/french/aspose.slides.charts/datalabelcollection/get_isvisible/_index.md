---
title: get_IsVisible()
second_title: Référence de l'API Aspose.Slides pour C++
description: False signifie que l'étiquette de données n'est pas visible par défaut (et donc tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false). Lecture seule bool.
type: docs
weight: 14
url: /fr/aspose.slides.charts/datalabelcollection/get_isvisible/
---
## DataLabelCollection::get_IsVisible() méthode

False signifie que l'étiquette de données n'est pas visible par défaut (et donc tous les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sont false). Lecture seule **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelCollection::get_IsVisible() override
```

## Remarques

Si l'étiquette de données est visible par défaut, vous pouvez la masquer par défaut avec [Hide()](../hide/) méthode. Mais si l'étiquette de données n'est pas visible par défaut (IsVisible est false) vous pouvez rendre l'étiquette de données \"visible 
par défaut\" en définissant les indicateurs Show*-flags (ShowValue, ...) de la propriété DefaultDataLabelFormat sur l'état true.

## Voir aussi

* Classe [DataLabelCollection](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)