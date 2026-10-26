---
title: set_R1C1Formula()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit la formule au format R1C1.
type: docs
weight: 92
url: /fr/aspose.slides.charts/ichartdatacell/set_r1c1formula/
---
## IChartDataCell::set_R1C1Formula(System::String) méthode


Définit la formule au format R1C1.

```cpp
virtual void Aspose::Slides::Charts::IChartDataCell::set_R1C1Formula(System::String value)=0
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