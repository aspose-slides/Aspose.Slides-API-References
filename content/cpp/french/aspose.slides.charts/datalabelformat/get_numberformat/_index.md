---
title: get_NumberFormat()
second_title: Référence API Aspose.Slides pour C++
description: "Représente la chaîne de format pour l'objet DataLabels. Lire System::String."
type: docs
weight: 27
url: /fr/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() méthode


Représente la chaîne de format pour l'objet DataLabels. Lire [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## Remarques



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Lorsque cette propriété est définie avec une valeur, cette valeur est également définie pour la propriété NumberFormat de toutes les étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/) (c'est à dire "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" provoque que tous les DataLabels[i].NumberFormat soient égaux à val). 



## Voir aussi

* Classe [String](../../../system/string/)
* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)