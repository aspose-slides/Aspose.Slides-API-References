---
title: get_ShowLeaderLines()
second_title: Référence de l'API Aspose.Slides for C++
description: Représente le comportement d’affichage des lignes de repère des étiquettes de données d’un graphique spécifié. True affiche les lignes de repère. False les masque. Lecture bool.
type: docs
weight: 248
url: /fr/aspose.slides.charts/idatalabelformat/get_showleaderlines/
---
## IDataLabelFormat::get_ShowLeaderLines() méthode

Représente le comportement d’affichage des lignes de repère des étiquettes de données d’un graphique spécifié. True affiche les lignes de repère. False les masque. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowLeaderLines()=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour toutes les étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" entraîne que toutes les DataLabels[i].ShowLeaderLines sont égales à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)