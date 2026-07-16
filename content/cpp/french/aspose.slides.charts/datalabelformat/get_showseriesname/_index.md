---
title: get_ShowSeriesName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un Boolean pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour le masquer. Lecture bool.
type: docs
weight: 170
url: /fr/aspose.slides.charts/datalabelformat/get_showseriesname/
---
## DataLabelFormat::get_ShowSeriesName() méthode

Renvoie un Boolean pour indiquer le comportement d’affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour le masquer. Lecture **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowSeriesName() override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. \"DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;\" entraîne que tous les DataLabels[i].ShowSeriesName sont égaux à val).

## Voir également

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)