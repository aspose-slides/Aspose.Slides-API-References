---
title: IChartDataPoint
second_title: Aspose.Sildes для .NET справка API
description: Представляет точку данных серии.
type: docs
weight: 1840
url: /ru/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint интерфейс

Представляет точку данных серии.

```csharp
public interface IChartDataPoint : IActualLayout
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIActualLayout](../../aspose.slides.charts/ichartdatapoint/asiactuallayout) { get; } | Возвращает интерфейс IActualLayout. |
| [BubbleSize](../../aspose.slides.charts/ichartdatapoint/bubblesize) { get; } | Получает размер пузыря точки данных диаграммы. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [CachedBubbleSize](../../aspose.slides.charts/ichartdatapoint/cachedbubblesize) { get; } | Получает кэшированный размер пузыря точки данных диаграммы. Только для чтения [`ICachedChartValue`](../icachedchartvalue). |
| [CachedValue](../../aspose.slides.charts/ichartdatapoint/cachedvalue) { get; } | Получает кэшированное значение точки данных диаграммы. Только для чтения [`ICachedChartValue`](../icachedchartvalue). |
| [CachedXValue](../../aspose.slides.charts/ichartdatapoint/cachedxvalue) { get; } | Получает кэшированное значение X точки данных диаграммы. Только для чтения [`ICachedChartValue`](../icachedchartvalue). |
| [CachedYValue](../../aspose.slides.charts/ichartdatapoint/cachedyvalue) { get; } | Получает кэшированное значение Y точки данных диаграммы. Только для чтения [`ICachedChartValue`](../icachedchartvalue). |
| [ColorValue](../../aspose.slides.charts/ichartdatapoint/colorvalue) { get; } | Получает значение цвета точки данных диаграммы. Используется с картами. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [DataPointLevels](../../aspose.slides.charts/ichartdatapoint/datapointlevels) { get; } | Возвращает контейнер уровней точек данных. Применяется для серий Treeamp и Sunburst. Индексация уровней точек данных начинается с нуля. |
| [ErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) { get; } | Представляет значения полос ошибок серии для типа значения Custom. Только для чтения [`IErrorBarsCustomValues`](../ierrorbarscustomvalues). |
| [Explosion](../../aspose.slides.charts/ichartdatapoint/explosion) { get; set; } | Указывает величину, на которую точка данных должна быть смещена от центра круговой диаграммы. Чтение/запись Int32. |
| [Format](../../aspose.slides.charts/ichartdatapoint/format) { get; set; } | Представляет свойства форматирования. Чтение/запись [`IFormat`](../iformat). |
| [Index](../../aspose.slides.charts/ichartdatapoint/index) { get; } | Определяет, к какой из коллекций дочерних элементов родителя относится эта точка данных. Чтение UInt32. |
| [InvertIfNegative](../../aspose.slides.charts/ichartdatapoint/invertifnegative) { get; set; } | Указывает, что точка данных должна инвертировать свои цвета, если значение отрицательное. Чтение/запись Boolean. |
| [IsBubble3D](../../aspose.slides.charts/ichartdatapoint/isbubble3d) { get; set; } | Указывает, что пузырям применяется 3-D эффект. Чтение/запись Boolean. |
| [Label](../../aspose.slides.charts/ichartdatapoint/label) { get; } | Представляет подпись точки данных диаграммы. Только для чтения [`IDataLabel`](../idatalabel). |
| [Marker](../../aspose.slides.charts/ichartdatapoint/marker) { get; } | Указывает маркер данных. Только для чтения [`IMarker`](../imarker). |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartdatapoint/relatedlegendentry) { get; } | Свойства соответствующей записи легенды для типов диаграмм из этого списка: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Только для чтения [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SetAsTotal](../../aspose.slides.charts/ichartdatapoint/setastotal) { get; set; } | Устанавливает точку данных как итоговую. Применяется только для серий типа Waterfall. |
| [SizeValue](../../aspose.slides.charts/ichartdatapoint/sizevalue) { get; } | Получает значение размера точки данных диаграммы. Используется с диаграммами Treemap и Sunburst. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [Value](../../aspose.slides.charts/ichartdatapoint/value) { get; } | Получает значение точки данных диаграммы. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |
| [XValue](../../aspose.slides.charts/ichartdatapoint/xvalue) { get; } | Получает значение x точки данных диаграммы. Только для чтения [`IStringOrDoubleChartValue`](../istringordoublechartvalue). |
| [YValue](../../aspose.slides.charts/ichartdatapoint/yvalue) { get; } | Получает значение y точки данных диаграммы. Только для чтения [`IDoubleChartValue`](../idoublechartvalue). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAutomaticDataPointColor](../../aspose.slides.charts/ichartdatapoint/getautomaticdatapointcolor)() | Возвращает автоматический цвет точки данных, основанный на индексе серии, индексе точки данных, свойстве ParentSeriesGroup.IsColorVaried и стиле диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined. |
| [Remove](../../aspose.slides.charts/ichartdatapoint/remove)() | Удаляет DataPoint из серии диаграммы. |

### См. также

* интерфейс [IActualLayout](../iactuallayout)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->