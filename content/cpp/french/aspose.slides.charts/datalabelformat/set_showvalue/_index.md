---
title: set_ShowValue()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur de pourcentage d'étiquette de données d'un graphique spécifié. True affiche la valeur de pourcentage. False pour masquer. Écrire bool.
type: docs
weight: 131
url: /fr/aspose.slides.charts/datalabelformat/set_showvalue/
---
## DataLabelFormat::set_ShowValue(bool) méthode

Représente le comportement d’affichage de la valeur de pourcentage d’étiquette de données d’un diagramme spécifié. True affiche la valeur de pourcentage. False pour masquer. Écrire **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowValue(bool value) override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d’étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowValue pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowValue pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire "DataLabels.DefaultDataLabelFormat.ShowValue = val;" entraîne que tous les DataLabels[i].ShowValue sont égaux à val). 

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)