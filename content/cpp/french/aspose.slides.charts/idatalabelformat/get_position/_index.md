---
title: get_Position()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente la position de l'étiquette de données. Lire LegendDataLabelPosition.
type: docs
weight: 66
url: /fr/aspose.slides.charts/idatalabelformat/get_position/
---
## IDataLabelFormat::get_Position() méthode

Représente la position de l'étiquette de données. Lire [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual LegendDataLabelPosition Aspose::Slides::Charts::IDataLabelFormat::get_Position()=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété Position pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Représente la position pour les objets [DataLabel](../../datalabel/). Définir cette propriété avec une valeur définit également cette valeur à la propriété Position pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. "DataLabels.DefaultDataLabelFormat.Position = val;" entraîne que tous les DataLabels[i].Position sont égaux à val). 

## Voir aussi

* Énumération [LegendDataLabelPosition](../../legenddatalabelposition/)
* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)