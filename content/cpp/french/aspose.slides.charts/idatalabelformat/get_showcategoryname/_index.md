---
title: get_ShowCategoryName()
second_title: Référence de l'API Aspose.Slides for C++
description: Représente le comportement d'affichage du nom de catégorie des libellés de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les libellés de données sur un graphique. False pour masquer. Lecture **bool**.
type: docs
weight: 144
url: /fr/aspose.slides.charts/idatalabelformat/get_showcategoryname/
---
## IDataLabelFormat::get_ShowCategoryName() méthode


Représente le comportement d'affichage du nom de catégorie des libellés de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les libellés de données sur un graphique. False pour masquer. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowCategoryName()=0
```

## Remarques


Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) de libellés de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouveaux libellés de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour tous les libellés de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" entraîne que tous les DataLabels[i].ShowCategoryName sont égaux à val). 


## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)