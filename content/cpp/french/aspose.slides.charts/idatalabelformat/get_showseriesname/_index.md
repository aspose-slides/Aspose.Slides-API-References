---
title: get_ShowSeriesName()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie un Boolean pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour le masquer. Lire bool.
type: docs
weight: 170
url: /fr/aspose.slides.charts/idatalabelformat/get_showseriesname/
---
## IDataLabelFormat::get_ShowSeriesName() méthode

Renvoie un Boolean pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour le masquer. Lire **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowSeriesName()=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowSeriesName de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause to all DataLabels[i].ShowSeriesName is equal to val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)