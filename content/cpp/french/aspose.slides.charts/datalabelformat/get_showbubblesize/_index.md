---
title: get_ShowBubbleSize()
second_title: Référence de l'API Aspose.Slides for C++
description: Représente le comportement d'affichage de la valeur de la taille de bulle du libellé de données d'un graphique spécifié. True affiche la valeur de la taille de bulle. False pour masquer. Lecture **bool**.
type: docs
weight: 222
url: /fr/aspose.slides.charts/datalabelformat/get_showbubblesize/
---
## DataLabelFormat::get_ShowBubbleSize() méthode

Représente le comportement d'affichage de la valeur de la taille de bulle du libellé de données d'un graphique spécifié. True affiche la valeur de la taille de bulle. False pour masquer. Lire **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowBubbleSize() override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) de libellés de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowBubbleSize pour les nouveaux libellés de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowBubbleSize pour tous les libellés de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est à dire \"DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;\" entraîne que tous les DataLabels[i].ShowBubbleSize sont égaux à val).

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)