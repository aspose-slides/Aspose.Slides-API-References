---
title: ChartDataPoint
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет данные точек серии.
type: docs
weight: 1250
url: /ru/aspose.slides.charts/chartdatapoint/
---

## Класс ChartDataPoint

Представляет данные точек серии.

```csharp
public class ChartDataPoint : IChartDataPoint
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/chartdatapoint/actualheight) { get; } | Указывает фактическую высоту элемента графика. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Читайте Single. |
| [ActualWidth](../../aspose.slides.charts/chartdatapoint/actualwidth) { get; } | Указывает фактическую ширину элемента графика. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Читайте Single. |
| [ActualX](../../aspose.slides.charts/chartdatapoint/actualx) { get; } | Указывает фактическое местоположение по оси x (слева) элемента графика относительно верхнего левого угла графика. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Читайте Single. |
| [ActualY](../../aspose.slides.charts/chartdatapoint/actualy) { get; } | Указывает фактическое верхнее положение элемента графика относительно верхнего левого угла графика. Вызовите метод IChart.ValidateChartLayout() перед получением фактических значений. Читайте Single. |
| [BubbleSize](../../aspose.slides.charts/chartdatapoint/bubblesize) { get; } | BubbleSize. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [ColorValue](../../aspose.slides.charts/chartdatapoint/colorvalue) { get; } | Возвращает цветовой индекс точки данных графика. Используется с картами. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/chartdatapoint/datapointlevels) { get; } | Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/chartdatapoint/errorbarscustomvalues) { get; } | Представляет значения столбцов погрешности серии в случае типа пользовательского значения. Только для чтения [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/chartdatapoint/explosion) { get; set; } | Указывает, насколько точка данных должна быть смещена от центра круговой диаграммы. Чтение/запись Int32. |
| [Format](../../aspose.slides.charts/chartdatapoint/format) { get; set; } | Представляет свойства форматирования. Чтение/запись [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/chartdatapoint/index) { get; } |  |
| [InvertIfNegative](../../aspose.slides.charts/chartdatapoint/invertifnegative) { get; set; } | Указывает, должна ли точка данных инвертировать свои цвета, если значение отрицательное. Чтение/запись Boolean. |
| [IsBubble3D](../../aspose.slides.charts/chartdatapoint/isbubble3d) { get; set; } | Указывает на применение 3-D эффекта к пузырькам. Чтение/запись Boolean. |
| [Label](../../aspose.slides.charts/chartdatapoint/label) { get; } | Метка. Только для чтения [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/chartdatapoint/marker) { get; } | Указывает маркер данных. Только для чтения [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/chartdatapoint/relatedlegendentry) { get; } | Свойства соответствующей записи легенды для типа графика из этого списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Только для чтения [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/chartdatapoint/setastotal) { get; set; } | Устанавливает точку данных в качестве итоговой. Применяется только для типа серии Waterfall. |
| [SizeValue](../../aspose.slides.charts/chartdatapoint/sizevalue) { get; } | Возвращает значение размера точки данных графика. Используется с диаграммами Treemap и Sunburst. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/chartdatapoint/value) { get; } | Значение. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/chartdatapoint/xvalue) { get; } | XValue. Только для чтения [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/chartdatapoint/yvalue) { get; } | YValue. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/chartdatapoint/getautomaticdatapointcolor)() | Возвращает автоматический цвет точки данных на основе индекса серии, индекса точки данных, свойства ParentSeriesGroup.IsColorVaried и стиля графика. Этот цвет используется по умолчанию, если FillType равен NotDefined. |
| [Remove](../../aspose.slides.charts/chartdatapoint/remove)() | Удаляет точку данных из серии графика. |

### См. также

* интерфейс [IChartDataPoint](../ichartdatapoint)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->