---
title: get_ShowLabelAsDataCallout()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si l'étiquette de données du graphique spécifié sera affichée comme annotation de données ou comme étiquette de données.
type: docs
weight: 274
url: /fr/aspose.slides.charts/idatalabelformat/get_showlabelasdatacallout/
---
## IDataLabelFormat::get_ShowLabelAsDataCallout() méthode

Détermine si l’étiquette de données du graphique spécifié sera affichée comme annotation de données ou comme étiquette de données.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelAsDataCallout()=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLabelAsDataCallout de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" entraîne que tous les DataLabels[i].ShowLabelAsDataCallout sont égaux à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)