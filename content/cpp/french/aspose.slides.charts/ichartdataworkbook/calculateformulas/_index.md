---
title: CalculateFormulas()
second_title: Référence de l'API Aspose.Slides pour C++
description: Calcule toutes les formules du classeur et met à jour les valeurs des cellules correspondantes.
type: docs
weight: 14
url: /fr/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() méthode


Calcule toutes les formules du classeur et met à jour les valeurs des cellules correspondantes.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## Remarques



L'exemple montre comment affecter une formule à la cellule et calculer une valeur. La valeur de la cellule \"B4\" est définie à 5. 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## Voir aussi

* Classe [IChartDataWorkbook](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)