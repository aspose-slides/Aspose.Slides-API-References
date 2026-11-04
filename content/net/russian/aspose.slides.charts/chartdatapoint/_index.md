---
title: ChartDataPoint
second_title: Aspose.Sildes для .NET справочник API
description: Представляет точку данных серии.
type: docs
weight: 1340
url: /ru/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint класс

Представляет точку данных серии.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Указывает фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения. Только для чтения Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Указывает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения. Только для чтения Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Указывает фактическое положение по оси X (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения. Только для чтения Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Указывает фактическую верхнюю позицию элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед этим, чтобы получить фактические значения. Только для чтения Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/chartdatapoint/cachedbubblesize) { get; } | Получает кэшированный размер пузыря точки данных диаграммы. Только для чтения [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/chartdatapoint/cachedvalue) { get; } | Получает кэшированное значение точки данных диаграммы. Только для чтения [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/chartdatapoint/cachedxvalue) { get; } | Получает кэшированное значение X точки данных диаграммы. Только для чтения [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/chartdatapoint/cachedyvalue) { get; } | Получает кэшированное значение Y точки данных диаграммы. Только для чтения [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Возвращает значение цвета точки данных диаграммы. Используется с картами. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Представляет значения полос ошибок серии в случае пользовательского типа значения. Только для чтения [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Указывает величину, на которую точка данных должна быть смещена от центра пирога. Чтение/запись Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Представляет свойства форматирования. Чтение/запись [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Указывает, что у пузырей применяется 3-D эффект. Чтение/запись Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Label. Только для чтения [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Указывает маркер данных. Только для чтения [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Свойства соответствующей записи легенды в случае типа диаграммы из следующего списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Только для чтения [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Устанавливает точку данных как итоговую. Применяется только для типа серии Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Возвращает значение размера точки данных диаграммы. Используется с диаграммами Treemap и Sunburst. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Value. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Только для чтения [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Удаляет DataPoint из серии диаграммы. |

### См. также

* интерфейс [IChartDataPoint](../ichartdatapoint)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->