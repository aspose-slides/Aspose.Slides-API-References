---
title: get_Formula()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la formule au format A1.
type: docs
weight: 53
url: /fr/aspose.slides.charts/chartdatacell/get_formula/
---
## ChartDataCell::get_Formula() méthode


Obtient la formule au format A1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_Formula() override
```

## Remarques



```cpp
auto cell = workbook->GetCell(0, u"B2");
cell->set_Formula(u"1 + SUM(F2:H5)");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ChartDataCell](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)