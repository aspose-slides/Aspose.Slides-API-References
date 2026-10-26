---
title: get_Value()
second_title: Référence API Aspose.Slides pour C++
description: "Obtient la valeur d'une cellule. Lire System::Object."
type: docs
weight: 27
url: /fr/aspose.slides.charts/ichartdatacell/get_value/
---
## IChartDataCell::get_Value() méthode


Obtient la valeur d'une cellule. Lire [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Charts::IChartDataCell::get_Value()=0
```

## Remarques



```cpp
workbook->GetCell(0, u"F2")->set_Value(System::ObjectExt::Box<double>(-2.5));
workbook->GetCell(0, u"G3")->set_Value(System::ObjectExt::Box<double>(6.3));
```




## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [IChartDataCell](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)