---
title: set_ShowPercentage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur en pourcentage du libellé de données d'un graphique spécifié. True affiche la valeur en pourcentage. False pour masquer. Écrire bool.
type: docs
weight: 209
url: /fr/aspose.slides.charts/idatalabelformat/set_showpercentage/
---
## IDataLabelFormat::set_ShowPercentage(bool) méthode


Représente le comportement d'affichage de la valeur en pourcentage du libellé de données d'un graphique spécifié. True affiche la valeur en pourcentage. False pour masquer. Écrire **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowPercentage(bool value)=0
```

## Remarques


Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est à dire \"DataLabels.DefaultDataLabelFormat.ShowPercentage = val;\" entraîne que tous les DataLabels[i].ShowPercentage sont égaux à val). 



## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)