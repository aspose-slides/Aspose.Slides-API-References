---
title: get_R1C1Formula()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la formule au format R1C1.
type: docs
weight: 79
url: /fr/aspose.slides.charts/chartdatacell/get_r1c1formula/
---
## ChartDataCell::get_R1C1Formula() méthode


Obtient la formule au format R1C1.

```cpp
System::String Aspose::Slides::Charts::ChartDataCell::get_R1C1Formula() override
```

## Remarques



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ChartDataCell](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)