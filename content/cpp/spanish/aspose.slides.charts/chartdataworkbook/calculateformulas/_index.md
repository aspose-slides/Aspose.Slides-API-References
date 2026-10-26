---
title: CalculateFormulas()
second_title: Referencia de la API de Aspose.Slides para C++
description: Calcula todas las fórmulas en el libro de trabajo y actualiza los valores de las celdas correspondientes.
type: docs
weight: 53
url: /es/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() método


Calcula todas las fórmulas en el libro de trabajo y actualiza los valores de las celdas correspondientes.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Observaciones



El ejemplo muestra cómo asignar una fórmula a la celda y calcular un valor. El valor de la celda \"B4\" se establece en 5.
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

## Ver también

* Clase [ChartDataWorkbook](../)
* Espacio de nombres [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)