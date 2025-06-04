---
title: IChart
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет графический график на слайде.
type: docs
weight: 1660
url: /ru/aspose.slides.charts/ichart/
---

## IChart интерфейс

Представляет графический график на слайде.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только чтение [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Позволяет получить базовый интерфейс IGraphicalObject. Только чтение [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Возвращает интерфейс IOverrideThemeable. Только чтение [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Предоставляет доступ к осям графика. Только чтение [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Возвращает объект, который позволяет изменить формат задней стены 3D графика. Только чтение [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Возвращает информацию о связанных или встроенных данных, связанных с графиком. Только чтение [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Возвращает таблицу данных графика. Только чтение [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Возвращает или устанавливает заголовок графика. Только чтение [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Возвращает или устанавливает способ отображения пустых ячеек на графике. Чтение/запись [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Возвращает объект, который позволяет изменить формат пола 3D графика. Только чтение [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Определяет, есть ли у графика таблица данных. Чтение/запись Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Определяет, есть ли у графика легенда. Чтение/запись Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Указывает, что область графика должна иметь закругленные углы. Чтение/запись Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Определяет, видим ли заголовок графика. Чтение/запись Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Возвращает или устанавливает легенду для графика. Только чтение [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Представляет область построения графика. Только чтение [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Определяет, должны ли быть нарисованы только видимые ячейки. Ложь для отображения как видимых, так и скрытых ячеек. Чтение/запись Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Возвращает 3D вращение графика. Только чтение [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Указывает, должны ли отображаться метки данных выше максимума графика. Чтение/запись Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Возвращает объект, который позволяет изменить формат боковой стены 3D графика. Только чтение [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Возвращает или устанавливает стиль графика. Чтение/запись [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Возвращает или устанавливает тип графика. Чтение/запись [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Указывает фигуры, нарисованные поверх графика. Только чтение [`IGroupShape`](../../aspose.slides/igroupshape). |

## Методы

| Название | Описание |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Вычисляет фактические значения элементов графика. Фактические значения включают положение элементов, реализующих интерфейс IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) и фактические значения осей (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### См. Также

* интерфейс [IFormattedTextContainer](../iformattedtextcontainer)
* интерфейс [IGraphicalObject](../../aspose.slides/igraphicalobject)
* интерфейс [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->