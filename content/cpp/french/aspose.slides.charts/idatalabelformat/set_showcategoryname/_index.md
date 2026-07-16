---
title: set_ShowCategoryName()
second_title: Référence API Aspose.Slides pour C++
description: Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données sur un graphique. False pour masquer. Write bool.
type: docs
weight: 157
url: /fr/aspose.slides.charts/idatalabelformat/set_showcategoryname/
---
## IDataLabelFormat::set_ShowCategoryName(bool) méthode

Représente le comportement d'affichage du nom de catégorie d'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données sur un graphique. False pour masquer. Write **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowCategoryName(bool value)=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowCategoryName de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire \"DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;\" entraîne que tous les DataLabels[i].ShowCategoryName sont égaux à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)