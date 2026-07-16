---
title: get_R1C1Formula()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la formule au format R1C1.
type: docs
weight: 79
url: /fr/aspose.slides.charts/ichartdatacell/get_r1c1formula/
---
## IChartDataCell::get_R1C1Formula() méthode

Obtient la formule au format R1C1.

```cpp
virtual System::String Aspose::Slides::Charts::IChartDataCell::get_R1C1Formula()=0
```

## Remarques



```cpp
auto cell = workbook->GetCell(0, u"C2");
cell->set_R1C1Formula(u"MAX(R2C6:R5C8) / 3");
```

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IChartDataCell](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)