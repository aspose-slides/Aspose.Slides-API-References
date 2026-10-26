---
title: get_ShowPercentage()
second_title: Référence API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur en pourcentage du libellé de données d'un graphique spécifié. True affiche la valeur en pourcentage. False pour masquer. Lecture bool.
type: docs
weight: 196
url: /fr/aspose.slides.charts/idatalabelformat/get_showpercentage/
---
## IDataLabelFormat::get_ShowPercentage() méthode

Représente le comportement d'affichage de la valeur en pourcentage du libellé de données d'un graphique spécifié. True affiche la valeur en pourcentage. False pour masquer. Lecture **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelFormat::get_ShowPercentage()=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) de libellés de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouveaux libellés de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage pour tous les libellés de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c'est-à-dire \"DataLabels.DefaultDataLabelFormat.ShowPercentage = val;\" entraîne que tous les DataLabels[i].ShowPercentage sont égaux à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)