---
title: set_ShowValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur en pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur en pourcentage. False pour masquer. Écrire bool.
type: docs
weight: 131
url: /fr/aspose.slides.charts/idatalabelformat/set_showvalue/
---
## IDataLabelFormat::set_ShowValue(bool) méthode

Représente le comportement d'affichage de la valeur en pourcentage de l'étiquette de données d'un graphique spécifié. True affiche la valeur en pourcentage. False pour masquer. Écrire **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowValue(bool value)=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" provoque que tous les DataLabels[i].ShowValue soient égaux à val).

## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)