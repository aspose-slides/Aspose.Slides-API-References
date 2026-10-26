---
title: set_Value()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Définit la valeur d'une cellule. Écrivez System::Object."
type: docs
weight: 40
url: /fr/aspose.slides.charts/ichartdatacell/set_value/
---
## IChartDataCell::set_Value(System::SharedPtr\<System::Object\>) méthode


Définit la valeur d'une cellule. Écrivez [System::Object](../../../system/object/).

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Value(System::SharedPtr<System::Object> value)=0
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
* Library [Aspose.Slides](../../../)