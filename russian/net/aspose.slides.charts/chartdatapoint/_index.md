---
title: ChartDataPoint
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет точку данных ряда.
type: docs
weight: 1190
url: /ru/net/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint class

Представляет точку данных ряда.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Определяет фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. ЧитатьSingle. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Задает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. ЧитатьSingle. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Задает фактическое положение x (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. ЧитатьSingle. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Указывает фактическую вершину элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. ЧитатьSingle. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | Размер пузыря. Только для чтения[`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Возвращает значение цвета точки данных диаграммы. Используется с диаграммами Map. Только для чтения[`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Представляет значения баров погрешностей серии в случае пользовательского типа значения. Только для чтения[`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Задает величину, на которую точка данных должна быть перемещена из центра круговой диаграммы. Чтение/записьInt32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Представляет свойства форматирования. Чтение/запись[`IFormat`](../iformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/записьBoolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Указывает, что к пузырькам применяется трехмерный эффект. Чтение/записьBoolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Метка. Только для чтения[`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Указывает маркер данных. Только для чтения[`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Свойства соответствующей записи легенды в случае типа диаграммы из этого списка: ChartType.BarOfPie, ChartType.ExplodedPie , ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Только для чтения[`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Устанавливает точку данных как общую. Применяется только для серии Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Возвращает значение размера точки данных диаграммы. Используется с диаграммами Treemap и Sunburst. Только для чтения[`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Значение. Только для чтения[`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Только для чтения[`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | Значение Y. Только для чтения[`IDoubleChartValue`](../idoublechartvalue). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля диаграммы. Этот цвет используется по умолчанию, если FillType равен NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Удаляет DataPoint из серии диаграмм. |

### Смотрите также

* interface [IChartDataPoint](../ichartdatapoint)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
