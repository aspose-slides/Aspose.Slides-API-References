---
title: get_ShowLabelValueFromCell()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur de la cellule d'étiquette de données d'un diagramme spécifié. True affiche la valeur de la cellule. False pour masquer. Lire bool.
type: docs
weight: 300
url: /fr/aspose.slides.charts/idatalabelformat/get_showlabelvaluefromcell/
---
## IDataLabelFormat::get_ShowLabelValueFromCell() méthode

Représente le comportement d'affichage de la valeur de la cellule d'étiquette de données d'un diagramme spécifié. True affiche la valeur de la cellule. False pour masquer. Lire **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLabelValueFromCell()=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLabelValueFromCell de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c'est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" entraîne que tous les DataLabels[i].ShowLabelValueFromCell sont égaux à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)