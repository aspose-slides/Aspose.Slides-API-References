---
title: IChart
second_title: Справка по API Aspose.Slides для .NET
description: Представляет графическую диаграмму на слайде.
type: docs
weight: 1660
url: /ru/aspose.slides.charts/ichart/
---

## Интерфейс IChart

Представляет графическую диаграмму на слайде.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только для чтения [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Позволяет получить базовый интерфейс IGraphicalObject. Только для чтения [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Возвращает интерфейс IOverrideThemeable. Только для чтения [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Предоставляет доступ к осям диаграммы. Только для чтения [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Возвращает объект, который позволяет изменить формат задней стены 3D-диаграммы. Только для чтения [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Возвращает информацию о связанных или встроенных данных, связанных с диаграммой. Только для чтения [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Возвращает таблицу данных диаграммы. Только для чтения [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Возвращает или устанавливает заголовок диаграммы. Только для чтения [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Возвращает или устанавливает способ отображения пустых ячеек на диаграмме. Чтение/запись [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Возвращает объект, который позволяет изменить формат пола 3D-диаграммы. Только для чтения [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Определяет, имеет ли диаграмма таблицу данных. Чтение/запись Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Определяет, имеет ли диаграмма легенду. Чтение/запись Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Указывает, что область диаграммы должна иметь закругленные углы. Чтение/запись Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Определяет, имеет ли диаграмма видимый заголовок. Чтение/запись Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Возвращает или устанавливает легенду для диаграммы. Только для чтения [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Представляет область построения диаграммы. Только для чтения [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Определяет, будут ли отображаться только видимые ячейки. Ложь для отображения как видимых, так и скрытых ячеек. Чтение/запись Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Возвращает 3D-вращение диаграммы. Только для чтения [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Указывает, что метки данных выше максимума диаграммы должны отображаться. Чтение/запись Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Возвращает объект, который позволяет изменить формат боковой стены 3D-диаграммы. Только для чтения [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Возвращает или устанавливает стиль диаграммы. Чтение/запись [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Возвращает или устанавливает тип диаграммы. Чтение/запись [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Указывает фигуры, нарисованные поверх диаграммы. Только для чтения [`IGroupShape`](../../aspose.slides/igroupshape). |

## Методы

| Название | Описание |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Рассчитывает актуальные значения элементов диаграммы. Актуальные значения включают положение элементов, которые реализуют интерфейс IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) и актуальные значения осей (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### См. Также

* интерфейс [IFormattedTextContainer](../iformattedtextcontainer)
* интерфейс [IGraphicalObject](../../aspose.slides/igraphicalobject)
* интерфейс [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->