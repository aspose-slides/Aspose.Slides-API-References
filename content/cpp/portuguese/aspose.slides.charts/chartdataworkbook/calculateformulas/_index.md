---
title: CalculateFormulas()
second_title: Referência da API Aspose.Slides para C++
description: Calcula todas as fórmulas na pasta de trabalho e atualiza os valores das células correspondentes.
type: docs
weight: 53
url: /pt/aspose.slides.charts/chartdataworkbook/calculateformulas/
---
## ChartDataWorkbook::CalculateFormulas() método


Calcula todas as fórmulas na pasta de trabalho e atualiza os valores das células correspondentes.

```cpp
void Aspose::Slides::Charts::ChartDataWorkbook::CalculateFormulas() override
```

## Observações



Exemplo mostra como atribuir uma fórmula à célula e calcular um valor. O valor da célula \"B4\" está sendo definido como 5. 
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

## Veja também

* Classe [ChartDataWorkbook](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Biblioteca [Aspose.Slides](../../../)