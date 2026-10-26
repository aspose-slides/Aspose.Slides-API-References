---
title: set_ShowCategoryName()
second_title: Référence API Aspose.Slides pour C++
description: Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données sur un graphique. False pour masquer. Écrire bool.
type: docs
weight: 157
url: /fr/aspose.slides.charts/datalabelformat/set_showcategoryname/
---
## DataLabelFormat::set_ShowCategoryName(bool) méthode


Représente le comportement d'affichage du nom de catégorie de l'étiquette de données d'un graphique spécifié. True pour afficher le nom de catégorie pour les étiquettes de données sur un graphique. False pour masquer. Écrire **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowCategoryName(bool value) override
```

## Remarques


Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowCategoryName pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowCategoryName pour toutes les étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire \"DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;\" entraîne que tous les DataLabels[i].ShowCategoryName sont égaux à val). 



## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)