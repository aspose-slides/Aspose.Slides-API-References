---
title: set_ShowLeaderLines()
second_title: Référence API Aspose.Slides pour C++
description: Représente le comportement d'affichage des lignes de repère des libellés de données d'un graphique spécifié. True affiche les lignes de repère. False les masque. Écriture bool.
type: docs
weight: 261
url: /fr/aspose.slides.charts/idatalabelformat/set_showleaderlines/
---
## IDataLabelFormat::set_ShowLeaderLines(bool) méthode

Représente le comportement d'affichage des lignes de repère des libellés de données d'un graphique spécifié. True affiche les lignes de repère. False les masque. Écriture **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLeaderLines(bool value)=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) de libellés de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouveaux libellés de données de la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLeaderLines pour tous les libellés de données de la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" entraîne que tous les DataLabels[i].ShowLeaderLines sont égaux à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)