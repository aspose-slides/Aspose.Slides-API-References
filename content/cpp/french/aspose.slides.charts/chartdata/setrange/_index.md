---
title: SetRange()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définissez la plage de données du graphique. Les séries et les catégories seront mises à jour en fonction de la nouvelle plage de données. Si le nombre de séries dans la plage de données est supérieur au nombre de séries dans les données du graphique, des séries supplémentaires du même type que la dernière série de la collection actuelle seront ajoutées à la fin de la collection.
type: docs
weight: 170
url: /fr/aspose.slides.charts/chartdata/setrange/
---
## ChartData::SetRange(System::String) méthode


Définissez la plage de données du graphique. Series et catégories seront mises à jour en fonction de la nouvelle plage de données. Si le nombre de series dans la plage de données est supérieur au nombre de series dans les données du graphique, des series supplémentaires du même type que la dernière series de la collection actuelle seront ajoutées à la fin de la collection.

```cpp
void Aspose::Slides::Charts::ChartData::SetRange(System::String formula) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | La formule de la plage de données des cellules. Par ex.: \"Sheet1!$A$1:$C$4\", \"SomeSheetName!A1:B100\", \"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5\". |

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ChartData](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)