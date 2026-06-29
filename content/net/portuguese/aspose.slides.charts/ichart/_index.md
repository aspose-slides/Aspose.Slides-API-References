---
title: IChart
second_title: Aspose.Sildes para .NET Referência da API
description: Representa um gráfico em um slide.
type: docs
weight: 1720
url: /pt/aspose.slides.charts/ichart/
---
## IChart interface

Representa um gráfico em um slide.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Permite obter a interface base IFormattedTextContainer. Somente leitura [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Permite obter a interface base IGraphicalObject. Somente leitura [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Retorna a interface IOverrideThemeable. Somente leitura [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Fornece acesso aos eixos do gráfico. Somente leitura [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Retorna um objeto que permite alterar o formato da parede traseira de um gráfico 3D. Somente leitura [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Retorna informações sobre os dados vinculados ou incorporados associados a um gráfico. Somente leitura [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Retorna uma tabela de dados de um gráfico. Somente leitura [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Retorna ou define o título do gráfico. Somente leitura [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Retorna ou define a forma de plotar células vazias em um gráfico. Leitura/Gravação [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Retorna um objeto que permite alterar o formato do piso de um gráfico 3D. Somente leitura [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Determina se um gráfico possui uma tabela de dados. Leitura/Gravação Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Determina se um gráfico possui uma legenda. Leitura/Gravação Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Especifica que a área do gráfico deve ter cantos arredondados. Leitura/Gravação Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Determina se um gráfico tem um título visível. Leitura/Gravação Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Retorna ou define uma legenda para um gráfico. Somente leitura [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Representa a área de plotagem de um gráfico. Somente leitura [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Determina se apenas as células visíveis são plotadas. Falso para plotar células visíveis e ocultas. Leitura/Gravação Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Retorna uma rotação 3D de um gráfico. Somente leitura [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Especifica que rótulos de dados acima do máximo do gráfico devem ser exibidos. Leitura/Gravação Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Retorna um objeto que permite alterar o formato da parede lateral de um gráfico 3D. Somente leitura [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Retorna ou define o estilo do gráfico. Leitura/Gravação [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Retorna ou define o tipo do gráfico. Leitura/Gravação [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Especifica as formas desenhadas sobre o gráfico. Somente leitura [`IGroupShape`](../../aspose.slides/igroupshape). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Calcula os valores reais dos elementos do gráfico. Os valores reais incluem a posição dos elementos que implementam a interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) e os valores reais dos eixos (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Veja Também

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->