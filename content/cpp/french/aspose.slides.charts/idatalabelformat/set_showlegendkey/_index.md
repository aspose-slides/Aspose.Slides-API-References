---
title: set_ShowLegendKey()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la clé de légende des étiquettes de données d'un graphique spécifié. Vrai si la clé de légende des étiquettes de données est visible. Écrire bool.
type: docs
weight: 105
url: /fr/aspose.slides.charts/idatalabelformat/set_showlegendkey/
---
## IDataLabelFormat::set_ShowLegendKey(bool) méthode


Représente le comportement d'affichage de la clé de légende des étiquettes de données d'un graphique spécifié. Vrai si la clé de légende des étiquettes de données est visible. Écrire **bool**.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_ShowLegendKey(bool value)=0
```

## Remarques


Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLegendKey pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur pour la propriété ShowLegendKey de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c'est-à-dire "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" provoque que tous les DataLabels[i].ShowLegendKey sont égaux à val). 


## Voir aussi

* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)