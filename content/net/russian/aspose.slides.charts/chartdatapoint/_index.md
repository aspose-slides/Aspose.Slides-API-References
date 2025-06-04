---
title: ChartDataPoint
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет данные точки серии.
type: docs
weight: 1250
url: /ru/aspose.slides.charts/chartdatapoint/
---

## Класс ChartDataPoint

Представляет данные точки серии.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Свойства

| Название | Описание |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Указывает фактическую высоту элемента графика. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. Читайте Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Указывает фактическую ширину элемента графика. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. Читайте Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Указывает фактическое расположение по оси X (влево) элемента графика относительно верхнего левого угла графика. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. Читайте Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Указывает фактическую верхнюю часть элемента графика относительно верхнего левого угла графика. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. Читайте Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | Размер пузырька. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Возвращает цветовое значение точки данных графика. Используется с картами. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Представляет значения ошибок серии в случае типа пользовательского значения. Только для чтения [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Указывает, на сколько точка данных будет перемещена от центра круговой диаграммы. Чтение/запись Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Представляет свойства форматирования. Чтение/запись [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Указывает, что пузырьки имеют эффект 3D. Чтение/запись Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Метка. Только для чтения [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Указывает маркер данных. Только для чтения [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Свойства соответствующей записи легенды в случае типа графика из этого списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Только для чтения [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Устанавливает точку данных как общую. Применяется только для типа серии Водопад. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Возвращает размерное значение точки данных графика. Используется с диаграммами Treemap и Sunburst. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Значение. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | Значение по оси X. Только для чтения [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | Значение по оси Y. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |

## Методы

| Название | Описание |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля графика. Этот цвет используется по умолчанию, если FillType равен NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Удаляет DataPoint из серии графика. |

### Также см.

* интерфейс [IChartDataPoint](../ichartdatapoint)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->