---
title: set_ShowLabelAsDataCallout()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine si l'étiquette de données du graphique spécifié sera affichée sous forme d'appel de données ou d'étiquette de données.
type: docs
weight: 287
url: /fr/aspose.slides.charts/idatalabelformat/set_showlabelasdatacallout/
---
## IDataLabelFormat::set_ShowLabelAsDataCallout(bool) méthode

Détermine si l'étiquette de données du graphique spécifié sera affichée sous forme d'appel de données ou d'étiquette de données.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLabelAsDataCallout(bool value)=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelAsDataCallout pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLabelAsDataCallout de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c'est à dire "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" entraîne que tous les DataLabels[i].ShowLabelAsDataCallout sont égaux à val). 

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)