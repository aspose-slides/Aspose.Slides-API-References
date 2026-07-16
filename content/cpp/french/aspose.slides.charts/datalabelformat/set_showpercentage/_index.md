---
title: set_ShowPercentage()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage de la valeur en pourcentage de l'étiquette de données d'un graphique spécifié. Vrai affiche la valeur en pourcentage. Faux pour masquer. Écrire bool.
type: docs
weight: 209
url: /fr/aspose.slides.charts/datalabelformat/set_showpercentage/
---
## DataLabelFormat::set_ShowPercentage(bool) méthode

Représente le comportement d'affichage de la valeur en pourcentage de l’étiquette de données d’un graphique spécifié. Vrai affiche la valeur en pourcentage. Faux pour masquer. Écrire **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowPercentage(bool value) override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d’étiquettes de données alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowPercentage pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété ShowPercentage pour toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. \"DataLabels.DefaultDataLabelFormat.ShowPercentage = val;\" entraîne que tous les DataLabels[i].ShowPercentage soient égaux à val).

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)