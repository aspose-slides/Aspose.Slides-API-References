---
title: set_UseSecondaryCategories()
second_title: Referência da API Aspose.Slides para C++
description: "Se definido como false então ChartData::get_SecondaryCategories retorna null e os dados em ChartData::get_Categories são usados tanto para séries primárias quanto secundárias. Se definido como true então os dados em ChartData::get_SecondaryCategories são usados para séries secundárias e os dados em ChartData::get_Categories são usados para séries primárias. Escreva bool."
type: docs
weight: 66
url: /pt/aspose.slides.charts/chartdata/set_usesecondarycategories/
---
## ChartData::set_UseSecondaryCategories(bool) método


Se definido como false então [ChartData::get_SecondaryCategories](../get_secondarycategories/) retorna null e os dados em [ChartData::get_Categories](../get_categories/) são usados tanto para as séries primárias quanto para as secundárias. Se definido como true então os dados em [ChartData::get_SecondaryCategories](../get_secondarycategories/) são usados para as séries secundárias e os dados em [ChartData::get_Categories](../get_categories/) são usados para as séries primárias. Escreva **bool**.

```cpp
void Aspose::Slides::Charts::ChartData::set_UseSecondaryCategories(bool value) override
```

## Observações


Exemplo. Quais categorias estão relacionadas às séries - [ChartData::get_Categories](../get_categories/) ou [ChartData::get_SecondaryCategories](../get_secondarycategories/)?
```cpp
if (series->get_PlotOnSecondAxis() && series->get_Chart()->get_ChartData()->get_UseSecondaryCategories())
{
    // categorias relacionadas são series->get_Chart()->get_ChartData()->get_SecondaryCategories()
}
else
{
    // categorias relacionadas são series->get_Chart()->get_ChartData()->get_Categories()
}
```

## Veja Também

* Classe [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)