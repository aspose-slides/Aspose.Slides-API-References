---
title: get_ShowValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur en pourcentage du libellé de données d'un graphique spécifié. True affiche la valeur en pourcentage. False la masque. Lire bool.
type: docs
weight: 118
url: /fr/aspose.slides.charts/datalabelformat/get_showvalue/
---
## DataLabelFormat::get_ShowValue() méthode

Représente le comportement d’affichage de la valeur en pourcentage du libellé de données d’un graphique spécifié. True affiche la valeur en pourcentage. False la masque. Lire **bool**.

```cpp
bool Aspose::Slides::Charts::DataLabelFormat::get_ShowValue() override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire "DataLabels.DefaultDataLabelFormat.ShowValue = val;" entraîne que tous les DataLabels[i].ShowValue sont égaux à val). 

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)