---
title: AddChart
second_title: Aspose.Sildes para .NET Referência da API
description: Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações e o adiciona ao final da coleção de formas.
type: docs
weight: 100
url: /pt/aspose.slides/shapecollection/addchart/
---
## AddChart(ChartType, float, float, float, float) {#addchart}

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | ChartType | O tipo de gráfico a ser adicionado. |
| x | Single | A coordenada x do novo gráfico, em pontos. |
| y | Single | A coordenada y do novo gráfico, em pontos. |
| width | Single | A largura do gráfico, em pontos. |
| height | Single | A altura do gráfico, em pontos. |

### Valor de Retorno

O [`IChart`](../../../aspose.slides.charts/ichart) recém-criado.

### Exemplos

O exemplo a seguir demonstra como criar um Chart em uma Apresentação do PowerPoint.

```csharp
[C#]
// Instancia a classe Presentation que representa um arquivo PPTX
using(Presentation pres = new Presentation()) {
  // Acessa o primeiro slide
  ISlide sld = pres.Slides[0];
  // Adiciona um gráfico com seus dados padrão
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Define o título do gráfico
  chart.ChartTitle.AddTextFrameForOverriding("Sample Title");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Define a primeira série para exibir valores
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Define o índice para a planilha de dados do gráfico
  int defaultWorksheetIndex = 0;
  // Obtém a planilha de dados do gráfico
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Exclui as séries e categorias geradas por padrão
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Adiciona novas séries
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.Type);
  // Adiciona novas categorias
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
  // Obtém a primeira série do gráfico
  IChartSeries series = chart.ChartData.Series[0];
  // Preenche os dados da série
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Define a cor de preenchimento da série
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Obtém a segunda série do gráfico
  series = chart.ChartData.Series[1];
  // Preenche os dados da série
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Define a cor de preenchimento da série
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Define o primeiro rótulo para mostrar o nome da Categoria
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Define a série para mostrar o valor no terceiro rótulo
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Salva o arquivo PPTX no disco
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Veja Também

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* classe [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Cria um novo gráfico, inicializa-o com dados de série de exemplo e configurações, e o adiciona ao final da coleção de formas.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| type | ChartType | O tipo de gráfico a ser adicionado. |
| x | Single | A coordenada x do novo gráfico, em pontos. |
| y | Single | A coordenada y do novo gráfico, em pontos. |
| width | Single | A largura do gráfico, em pontos. |
| height | Single | A altura do gráfico, em pontos. |
| initWithSample | Boolean | True para inicializar o novo gráfico com dados de série de exemplo e configurações; false para criar o gráfico sem séries e apenas com configurações mínimas, o que torna a criação mais rápida. |

### Valor de Retorno

O [`IChart`](../../../aspose.slides.charts/ichart) recém-criado.

### Veja Também

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* classe [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->