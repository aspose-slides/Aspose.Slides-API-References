---
title: set_Separator()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique. Écrire System::String."
type: docs
weight: 339
url: /fr/aspose.slides.charts/idatalabelformat/set_separator/
---
## IDataLabelFormat::set_Separator(System::String) méthode

Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique. Écrivez [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_Separator(System::String value)=0
```

## Remarques

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété Separator pour toutes les étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/) (c’est-à-dire "DataLabels.DefaultDataLabelFormat.Separator = val;" entraîne que tous les DataLabels[i].Separator sont égaux à val). 

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)