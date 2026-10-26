---
title: get_ShowLegendKey()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la clé de légende des étiquettes de données d'un graphique spécifié. Vrai si la clé de légende des étiquettes de données est visible. Lecture bool.
type: docs
weight: 92
url: /fr/aspose.slides.charts/datalabelformat/get_showlegendkey/
---
## DataLabelFormat::get_ShowLegendKey() méthode

Représente le comportement d'affichage de la clé de légende des étiquettes de données d'un graphique spécifié. Vrai si la clé de légende des étiquettes de données est visible. Lecture **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowLegendKey() override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLegendKey pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" provoque que tous les DataLabels[i].ShowLegendKey soient égaux à val).

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)