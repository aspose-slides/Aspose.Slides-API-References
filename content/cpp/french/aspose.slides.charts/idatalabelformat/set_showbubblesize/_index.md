---
title: set_ShowBubbleSize()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur de taille de bulle d'étiquette de données d'un graphique spécifié. True affiche la valeur de taille de bulle. False la masque. Écrire bool.
type: docs
weight: 235
url: /fr/aspose.slides.charts/idatalabelformat/set_showbubblesize/
---
## IDataLabelFormat::set_ShowBubbleSize(bool) méthode

Représente le comportement d'affichage de la valeur de taille de bulle d'étiquette de données d'un graphique spécifié. True affiche la valeur de taille de bulle. False la masque. Écrire **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowBubbleSize(bool value)=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" entraîne que tous les DataLabels[i].ShowBubbleSize sont égaux à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)