---
title: set_Formula()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la formule au format A1.
type: docs
weight: 66
url: /fr/aspose.slides.charts/chartdatacell/set_formula/
---
## ChartDataCell::set_Formula(System::String) méthode

Définit la formule au format A1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_Formula(System::String value) override
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