---
title: set_ShowSeriesName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit un booléen pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour masquer. Écrire bool.
type: docs
weight: 183
url: /fr/aspose.slides.charts/datalabelformat/set_showseriesname/
---
## DataLabelFormat::set_ShowSeriesName(bool) méthode


Définit un booléen pour indiquer le comportement d'affichage du nom de la série pour les étiquettes de données sur un graphique. True pour afficher le nom de la série. False pour masquer. Écrire **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowSeriesName(bool value) override
```

## Remarques


Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowSeriesName pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowSeriesName pour toutes les étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause que tous les DataLabels[i].ShowSeriesName sont égaux à val). 



## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)