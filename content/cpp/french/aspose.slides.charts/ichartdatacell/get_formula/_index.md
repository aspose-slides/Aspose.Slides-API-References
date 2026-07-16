---
title: get_Formula()
second_title: Référence API Aspose.Slides pour C++
description: Obtient la formule au format A1.
type: docs
weight: 53
url: /fr/aspose.slides.charts/ichartdatacell/get_formula/
---
## IChartDataCell::get_Formula() méthode


Obtient la formule au format A1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_Formula()=0
```

## Remarques



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IChartDataCell](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)