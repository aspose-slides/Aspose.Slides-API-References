---
title: set_NumberFormat()
second_title: Référence API Aspose.Slides pour C++
description: "Représente la chaîne de format pour l'objet DataLabels. Écrivez System::String."
type: docs
weight: 40
url: /fr/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) method


Représente la chaîne de format pour l'objet DataLabels. Écrivez [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## Remarques



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Lorsque cette propriété est définie avec une valeur, cette valeur est également appliquée à la propriété NumberFormat pour toutes les étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/) (c.-à-d. \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" provoque que tous les DataLabels[i].NumberFormat soient égaux à val). 
## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)