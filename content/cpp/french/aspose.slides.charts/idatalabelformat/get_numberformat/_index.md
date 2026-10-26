---
title: get_NumberFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente la chaîne de format pour l'objet DataLabels. Lire System::String."
type: docs
weight: 27
url: /fr/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() méthode

Représente la chaîne de format pour l'objet DataLabels. Lire [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## Remarques

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

Si le parent de cet objet [DataLabelFormat](../../datalabelformat/) est une collection [DataLabelCollection](../../datalabelcollection/) d'étiquettes de données, alors cette propriété obtient ou définit la valeur par défaut de la propriété NumberFormat pour les nouvelles étiquettes de données dans la collection [DataLabelCollection](../../datalabelcollection/). Lorsque cette propriété est définie avec une valeur, cette valeur est également appliquée à la propriété NumberFormat pour toutes les étiquettes de données de la collection [DataLabelCollection](../../datalabelcollection/) (c'est-a-dire \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" entraîne que tous les DataLabels[i].NumberFormat soient égaux à val).

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IDataLabelFormat](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)