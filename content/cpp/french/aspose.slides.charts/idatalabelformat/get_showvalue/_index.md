---
title: get_ShowValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lire bool.
type: docs
weight: 118
url: /fr/aspose.slides.charts/idatalabelformat/get_showvalue/
---
## IDataLabelFormat::get_ShowValue() méthode

Représente le comportement d'affichage de la valeur de pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Lire **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowValue()=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause à ce que tous les DataLabels[i].ShowValue soient égaux à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)