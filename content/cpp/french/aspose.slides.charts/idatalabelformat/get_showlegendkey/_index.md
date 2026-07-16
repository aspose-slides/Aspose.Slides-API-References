---
title: get_ShowLegendKey()
second_title: Référence de l'API Aspose.Slides for C++
description: Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. Vrai si la clé de légende de l'étiquette de données est visible. Lecture bool.
type: docs
weight: 92
url: /fr/aspose.slides.charts/idatalabelformat/get_showlegendkey/
---
## IDataLabelFormat::get_ShowLegendKey() méthode

Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. Vrai si la clé de légende de l'étiquette de données est visible. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLegendKey()=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLegendKey pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" entraîne que tous les DataLabels[i].ShowLegendKey sont égaux à val). 


## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)