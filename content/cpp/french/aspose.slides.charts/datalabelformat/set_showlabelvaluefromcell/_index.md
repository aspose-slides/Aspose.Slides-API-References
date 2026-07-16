---
title: set_ShowLabelValueFromCell()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur de cellule d'étiquette de données d'un graphique spécifié. True affiche la valeur de la cellule. False masque. Écrire bool.
type: docs
weight: 287
url: /fr/aspose.slides.charts/datalabelformat/set_showlabelvaluefromcell/
---
## DataLabelFormat::set_ShowLabelValueFromCell(bool) méthode

Représente le comportement d'affichage de la valeur de cellule d'étiquette de données d'un graphique spécifié. True affiche la valeur de la cellule. False masque. Écrire **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowLabelValueFromCell(bool value) override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLabelValueFromCell pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowLabelValueFromCell pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" entraîne que tous les DataLabels[i].ShowLabelValueFromCell sont égaux à val).

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)