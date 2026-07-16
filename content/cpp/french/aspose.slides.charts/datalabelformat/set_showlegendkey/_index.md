---
title: set_ShowLegendKey()
second_title: Référence API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. True si la clé de légende de l'étiquette de données est visible. Écrire bool.
type: docs
weight: 105
url: /fr/aspose.slides.charts/datalabelformat/set_showlegendkey/
---
## DataLabelFormat::set_ShowLegendKey(bool) méthode

Représente le comportement d'affichage de la clé de légende de l'étiquette de données d'un graphique spécifié. True si la clé de légende de l'étiquette de données est visible. Écrire **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowLegendKey(bool value) override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété récupère ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLegendKey de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. \"DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;\" entraîne que tous les DataLabels[i].ShowLegendKey sont égaux à val).

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)