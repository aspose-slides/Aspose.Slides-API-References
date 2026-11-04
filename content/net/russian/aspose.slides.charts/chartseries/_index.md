---
title: ChartSeries
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет серию диаграммы.
type: docs
weight: 1450
url: /ru/aspose.slides.charts/chartseries/
---
## ChartSeries класс

Представляет серию диаграммы.

```csharp
public class ChartSeries : IChartSeries
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Указывает форму серии 3-D столбчатой диаграммы. Изменение значения этого свойства может привести к автоматическому изменению Type серии. Чтение/запись [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Указывает, как значения размеров пузырей представлены на пузырчатой диаграмме. Это свойство относится не только к данной серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительской серии. Используйте свойство ParentSeriesGroup.BubbleSizeRepresentation чтение/запись. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Указывает коэффициент масштабирования для пузырчатой диаграммы (может быть от 0 до 300 % от размера по умолчанию). Это свойство относится не только к данной серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительской серии. Используйте свойство ParentSeriesGroup.BubbleSizeScale чтение/запись для изменения значения. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Возвращает родительскую диаграмму. Только для чтения [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Возвращает коллекцию точек данных этой серии. Только для чтения [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). Это свойство относится не только к данной серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительской серии. Используйте свойство ParentSeriesGroup.DoughnutHoleSize чтение/запись для изменения значения. Только для чтения Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Представляет ErrorBars серии с направлением X. ErrorBars с направлением X доступны для серий типов area, bar, scatter и bubble. Для остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с свойством [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Только для чтения [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Представляет ErrorBars серии с направлением Y. ErrorBars с направлением Y доступны для серий типов area, bar, line, scatter и bubble. Для остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с свойством [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Только для чтения [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Расстояние открытого куска пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. Чтение/запись Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Указывает угол первого куска пирога или кольцевой диаграммы в градусах (по часовой стрелке от верхней точки, от 0 до 360 градусов). Это свойство относится не только к данной серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительской серии. Используйте свойство ParentSeriesGroup.FirstSliceAngle чтение/запись для изменения значения. Только для чтения UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Возвращает формат серии. Только для чтения [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Возвращает или задает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. Это свойство относится не только к данной серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительской серии. Используйте свойство ParentSeriesGroup.GapDepth чтение/запись для изменения значения. Только для чтения Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Это свойство относится не только к данной серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительской серии. Используйте свойство ParentSeriesGroup.GapWidth чтение/запись для изменения значения. Только для чтения Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Определяет, есть ли линии серии для этой серии и родственных серий. Используйте свойство ParentSeriesGroup.HasSeriesLines чтение/запись для изменения значения. Используйте свойство ParentSeriesGroup.SeriesLinesFormat для форматирования линий серии. Только для чтения Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Определяет, содержит ли линейная или биржевая диаграмма верхние/нижние бары. Используйте свойство ParentSeriesGroup.UpDownBars.HasUpDownBars чтение/запись для изменения значения. Используйте свойство ParentSeriesGroup.UpDownBars для форматирования верхних/нижних баров. Только для чтения Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Указывает инвертированный сплошной цвет для серии. Чтобы применить настройку цвета, установите FillType формата серии в FillType.Solid. Чтение/запись [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Указывает, что столбцовая, колонковая или пузырчатая серия должна инвертировать свои цвета, если значение отрицательное. Чтение/запись Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Указывает, что каждый маркер данных в серии имеет разный цвет. Используйте свойство ParentSeriesGroup.IsColorVaried чтение/запись для изменения значения. Только для чтения Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Возвращает Labels серии. Только для чтения [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Маркер. Только для чтения [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Возвращает название серии. Только для чтения [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Чтение/запись String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Чтение/запись String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Чтение/запись String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Чтение/запись String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Возвращает порядок серии. Чтение/запись Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Указывает, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100 % до 100 %). Это свойство относится не только к данной серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Чтобы изменить значение, используйте свойство !:ParentSeriesGroup.Overlap чтение/запись. Только для чтения SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Представляет макет меток родительской категории. Применяется только к диаграммам Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Только для чтения [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Указывает, как определить, какие точки данных находятся во второй части пирога или столбце в диаграмме pie-of-pie или bar-of-pie. Используйте свойство ParentSeriesGroup.PieSplitBy чтение/запись для изменения значения. Только для чтения [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Пользовательская информация о разбиении для диаграммы pie-of-pie или bar-of-pie с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во второй части пирога или столбце в такой диаграмме. Это свойство относится не только к данной серии, но и ко всем сериям группы родительской серии — это проекция соответствующего свойства группы. Только для чтения [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Указывает значение, используемое для определения, какие точки данных находятся во второй части пирога или столбце в диаграмме pie-of-pie или bar-of-pie. Используется вместе со свойством PieSplitBy. Используйте свойство ParentSeriesGroup.PieSplitPosition чтение/запись для изменения значения. Только для чтения Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Указывает, построена ли эта серия по вторичной оси. Чтение/запись Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Представляет метод квартилей. Применяется только к диаграммам BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Представляет запись легенды, связанную с этой серией. Только для чтения [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Указывает размер второй части пирога или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого пирога (может быть от 5 % до 200 %). Используйте свойство ParentSeriesGroup.SecondPieSize чтение/запись для изменения значения. Только для чтения UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Представляет линии соединения. Применяется только к диаграммам Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Представляет внутренние точки. Истинно, если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Представляет линию среднего. Истинно, если линия среднего отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Представляет маркеры среднего. Истинно, если маркеры среднего отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Представляет выбросы. Истинно, если выбросы отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Представляет сглаживание кривой. Истинно, если сглаживание включено для линейной или точечной диаграммы. Применяется только к линейным и точечным диаграммам, соединённым линиями. Чтение/запись Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Коллекция линий тренда серии. Только для чтения [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Возвращает тип этой серии. Чтение/запись [`ChartType`](../charttype). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Возвращает автоматический цвет серии, основанный на индексе серии и стиле диаграммы. Этот цвет используется по умолчанию, если FillType равно NotDefined. |

### См. также

* интерфейс [IChartSeries](../ichartseries)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->