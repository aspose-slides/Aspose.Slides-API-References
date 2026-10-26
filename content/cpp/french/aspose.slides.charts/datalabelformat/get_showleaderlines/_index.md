---
title: get_ShowLeaderLines()
second_title: Référence API Aspose.Slides pour C++
description: Représente le comportement d'affichage des repères de lignes d'étiquettes de données d'un graphique spécifié. True affiche les repères de lignes. False les masque. Lecture bool.
type: docs
weight: 248
url: /fr/aspose.slides.charts/datalabelformat/get_showleaderlines/
---
## DataLabelFormat::get_ShowLeaderLines() méthode

Représente le comportement d'affichage des repères de lignes d'étiquette de données d'un graphique spécifié. True affiche les repères de lignes. False les masque. Lecture **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowLeaderLines() override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c'est-a-dire "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" provoque que tous les DataLabels[i].ShowLeaderLines sont égaux à val).

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)