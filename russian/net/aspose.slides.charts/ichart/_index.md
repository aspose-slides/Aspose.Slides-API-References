---
title: IChart
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет графическую диаграмму на слайде.
type: docs
weight: 1600
url: /ru/net/aspose.slides.charts/ichart/
---
## IChart interface

Представляет графическую диаграмму на слайде.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только для чтения[`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Позволяет получить базовый интерфейс IGraphicalObject. Только для чтения[`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Возвращает интерфейс IOverrideThemeable. Только для чтения[`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Предоставляет доступ к осям диаграммы. Только для чтения[`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Возвращает объект, позволяющий изменить формат задней стенки трехмерного графика. Только чтение[`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Возвращает информацию о связанных или встроенных данных, связанных с диаграммой. Только для чтения[`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Возвращает таблицу данных диаграммы. Только для чтения[`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Возвращает или задает заголовок диаграммы Только для чтения[`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Возвращает или задает способ отображения пустых ячеек на диаграмме. Чтение/запись[`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Возвращает объект, позволяющий изменить формат пола трехмерного графика. Только чтение[`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Определяет, имеет ли диаграмма таблицу данных. Чтение/записьBoolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Определяет, есть ли у диаграммы легенда. Чтение/записьBoolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Указывает, что область диаграммы должна иметь закругленные углы. Чтение/записьBoolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Определяет, имеет ли диаграмма видимый заголовок. Чтение/записьBoolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Возвращает или задает легенду для диаграммы. Только для чтения[`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Представляет область построения диаграммы. Только для чтения[`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Определяет, отображаются ли на графике только видимые ячейки. False для отображения как видимых, так и скрытых ячеек. Чтение/записьBoolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Возвращает трехмерный поворот диаграммы. Только для чтения[`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Указывает, что должны отображаться метки данных, превышающие максимум диаграммы. Чтение/записьBoolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Возвращает объект, позволяющий изменить формат боковой стенки трехмерного графика. Только чтение[`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Возвращает или задает стиль диаграммы. Чтение/запись[`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Возвращает или задает тип диаграммы. Чтение/запись[`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Укажите фигуры, нарисованные поверх диаграммы. Только для чтения[`IGroupShape`](../../aspose.slides/igroupshape). |

## Методы

| Имя | Описание |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Вычисляет фактические значения элементов диаграммы. Фактические значения включают положение элементов, которые реализуют интерфейс IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) и фактические значения осей (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Смотрите также

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
