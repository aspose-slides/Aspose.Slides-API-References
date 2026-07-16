---
title: set_ShowLeaderLines()
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente le comportement d'affichage des lignes directrices des étiquettes de données d'un graphique spécifié. True affiche les lignes directrices. False les masque. Écriture bool.
type: docs
weight: 261
url: /fr/aspose.slides.charts/datalabelformat/set_showleaderlines/
---
## DataLabelFormat::set_ShowLeaderLines(bool) method

Représente le comportement d'affichage des lignes directrices des étiquettes de données d'un graphique spécifié. True affiche les lignes directrices. False les masque. Écriture **bool**.

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_ShowLeaderLines(bool value) override
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété ShowLeaderLines pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur modifie également cette valeur pour la propriété ShowLeaderLines de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. \"DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;\" entraîne que tous les DataLabels[i].ShowLeaderLines sont égaux à val).

## Voir aussi

* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)