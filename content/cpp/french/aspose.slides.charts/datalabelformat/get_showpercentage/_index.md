---
title: get_ShowPercentage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur du pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur du pourcentage. False la masque. Lecture bool.
type: docs
weight: 196
url: /fr/aspose.slides.charts/datalabelformat/get_showpercentage/
---
## DataLabelFormat::get_ShowPercentage() méthode

Représente le comportement d'affichage de la valeur du pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur du pourcentage. False la masque. Lecture **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowPercentage() override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowPercentage de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire \"DataLabels.DefaultDataLabelFormat.ShowPercentage = val;\" entraîne que tous les DataLabels[i].ShowPercentage sont égaux à val).

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)