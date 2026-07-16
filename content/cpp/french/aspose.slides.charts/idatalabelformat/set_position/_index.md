---
title: set_Position()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente la position de l'étiquette de données. Écrivez LegendDataLabelPosition.
type: docs
weight: 79
url: /fr/aspose.slides.charts/idatalabelformat/set_position/
---
## IDataLabelFormat::set_Position(LegendDataLabelPosition) méthode

Représente la position de l'étiquette de données. Écrivez [LegendDataLabelPosition](../../legenddatalabelposition/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Position(LegendDataLabelPosition value)=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Position pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Représente la position pour les objets [DataLabel](../../datalabel/). Définir cette propriété avec une valeur définit également cette valeur à la propriété Position pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire "DataLabels.DefaultDataLabelFormat.Position = val;" cause à tous les DataLabels[i].Position d'être égal à val).

## Voir aussi

* Enum [LegendDataLabelPosition](../../legenddatalabelposition/)
* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)