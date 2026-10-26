---
title: set_NumberFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente la chaîne de format pour l'objet DataLabels. Écrivez System::String."
type: docs
weight: 40
url: /fr/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) méthode


Représente la chaîne de format pour l'objet DataLabels. Écrivez [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## Remarques



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





Si le parent de cet objet [DataLabelFormat](../) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Lorsque cette propriété est définie avec une valeur, cette valeur est également affectée à la propriété NumberFormat pour toutes les étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/) (c'est à dire "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" entraîne que tous les DataLabels[i].NumberFormat soient égaux à val). 


## Voir aussi

* Classe [String](../../../system/string/)
* Classe [DataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)