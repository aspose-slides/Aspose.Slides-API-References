---
title: get_Overlap()
second_title: Referência da API Aspose.Slides para C++
description: Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como uma porcentagem (de -100% a 100%).
type: docs
weight: 157
url: /pt/aspose.slides.charts/chartseriesgroup/get_overlap/
---
## ChartSeriesGroup::get_Overlap() método


Especifica quanto as barras e colunas devem se sobrepor em gráficos 2-D, como uma porcentagem (de -100% a 100%).

```cpp
int8_t Aspose::Slides::Charts::ChartSeriesGroup::get_Overlap() override
```

## Observações


* -100%: Espaçamento máximo (as barras estão completamente separadas).
* 0%: As barras são colocadas lado a lado sem sobreposição ou espaçamento.
* 100%: Sobreposição máxima (as barras se sobrepõem completamente). Esta propriedade é leitura/gravação **int8_t**.



O exemplo a seguir demonstra como definir a sobreposição para um grupo de séries de gráfico e renderizar o gráfico resultante em um formulário: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<ISlide> slide = pres->get_Slide(0);

System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 10.0f, 10.0f, 600.0f, 300.0f);
System::SharedPtr<IChartSeriesCollection> series = chart->get_ChartData()->get_Series();
series->idx_get(0)->get_ParentSeriesGroup()->set_Overlap(55); // Define a sobreposição para 55%

auto image = slide->GetImage(1.0f, 1.0f);
image->Save(u"image.png", ImageFormat::Png);
```


## Veja Também

* Classe [ChartSeriesGroup](../)
* Espaço de nomes [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)