---
title: get_Separator()
second_title: Référence API Aspose.Slides pour C++
description: "Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique. Lire System::String."
type: docs
weight: 326
url: /fr/aspose.slides.charts/idatalabelformat/get_separator/
---
## IDataLabelFormat::get_Separator() méthode


Définit ou renvoie un Variant représentant le séparateur utilisé pour les étiquettes de données d'un graphique. Lire [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_Separator()=0
```

## Remarques


Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété Separator pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Définir cette propriété avec une valeur définit également cette valeur à la propriété Separator pour toutes les étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. \"DataLabels.DefaultDataLabelFormat.Separator = val;\" cause que tous les DataLabels[i].Separator sont égaux à val). 


## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)