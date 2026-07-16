---
title: set_R1C1Formula()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la formule au format R1C1.
type: docs
weight: 92
url: /fr/aspose.slides.charts/chartdatacell/set_r1c1formula/
---
## ChartDataCell::set_R1C1Formula(System::String) méthode


Définit la formule au format R1C1.

```cpp
void Aspose::Slides::Charts::ChartDataCell::set_R1C1Formula(System::String value) override
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
* Library [Aspose.Slides](../../../)