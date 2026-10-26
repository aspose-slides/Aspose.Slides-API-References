---
title: set_Formula()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la formule au format A1.
type: docs
weight: 66
url: /fr/aspose.slides.charts/ichartdatacell/set_formula/
---
## IChartDataCell::set_Formula(System::String) méthode

Définit la formule au format A1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_Formula(System::String value)=0
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