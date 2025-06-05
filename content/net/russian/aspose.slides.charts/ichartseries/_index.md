---
title: IChartSeries
second_title: Aspose.Sildes для .NET API Reference
description: Представляет серию графиков.
type: docs
weight: 1850
url: /ru/aspose.slides.charts/ichartseries/
---

## Интерфейс IChartSeries

Представляет серию графиков.

```csharp
public interface IChartSeries : IChartComponent
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | Позволяет получить базовый интерфейс IChartComponent. Только для чтения [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | Указывает форму серии 3-D столбчатой диаграммы. Изменение значения этого свойства может привести к автоматическому изменению типа серии. Чтение/запись [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | Указывает, как значения размеров пузырьков представлены на диаграмме пузырьков. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.BubbleSizeRepresentation для изменения значения. |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | Указывает коэффициент масштабирования для диаграммы пузырьков (может быть от 0 до 300 процентов от стандартного размера). Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.BubbleSizeScale для изменения значения. |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | Возвращает коллекцию точек данных этой серии. Только для чтения [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | Указывает размер отверстия в круговой диаграмме (может быть от 10 до 90 процентов от размера области графика). Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.DoughnutHoleSize для изменения значения. Только для чтения Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | Представляет ErrorBars серии с направлением X. ErrorBars в направлении X доступны для серии типа область, столбец, разброс и пузырь. Для любых других типов диаграмм это свойство возвращает null (включая 3D диаграммы). В случае пользовательских значений используйте коллекцию DataPoints, чтобы указать значение (с помощью свойства [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Только для чтения [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Представляет ErrorBars серии с направлением Y. ErrorBars в направлении Y доступны для серии типа область, столбец, линия, разброс и пузырь. Для любых других типов диаграмм это свойство возвращает null (включая 3D диаграммы). В случае пользовательских значений используйте коллекцию DataPoints, чтобы указать значение (с помощью свойства [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Только для чтения [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | Расстояние открытого сектора пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. Чтение/запись Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | Указывает угол первого сегмента круговой или кольцевой диаграммы, в градусах (по часовой стрелке сверху, от 0 до 360 градусов). Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.FirstSliceAngle для изменения значения. Только для чтения UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | Возвращает формат серии. Только для чтения [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | Возвращает или устанавливает расстояние, в процентах от ширины маркера, между рядами данных в 3D диаграмме. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.GapDepth для изменения значения. Только для чтения Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | Указывает пространство между кластерами столбцов или баров, в процентах от ширины столбца или бар. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.GapWidth для изменения значения. Только для чтения Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | Определяет, есть ли линии серий для этой серии и связанных серий. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.HasSeriesLines для изменения значения. Используйте свойство ParentSeriesGroup.SeriesLinesFormat для формата линий серий. Только для чтения Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | Определяет, есть ли на линейной или фондовой диаграмме бары вверх/вниз. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.UpDownBars.HasUpDownBars для изменения значения. Используйте свойство ParentSeriesGroup.UpDownBars для формата баров вверх/вниз. Только для чтения Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | Указывает инвертированный сплошной цвет для серии. Чтобы применить настройку цвета, установите формат серии FillType в FillType.Solid. Чтение/запись [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | Указывает, что столбцовая, круговая или пузырьковая серия должна инвертировать свои цвета, если значение отрицательное. Чтение/запись Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | Указывает, что каждый маркер данных в серии имеет разный цвет. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.IsColorVaried для изменения значения. Только для чтения Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | Возвращает метки серии. Только для чтения [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | Возвращает маркер серии. Только для чтения [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | Возвращает имя серии. Только для чтения [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | Возвращает или устанавливает числовой формат для размеров пузырьков серии. Чтение/запись String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | Возвращает или устанавливает числовой формат для значений серии. Чтение/запись String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | Возвращает или устанавливает числовой формат для значений X серии. Чтение/запись String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | Возвращает или устанавливает числовой формат для значений Y серии. Чтение/запись String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | Возвращает порядок серии. Чтение/запись Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | Указывает, насколько столбцы и бары перекрываются на 2-D диаграммах, в процентах (от -100% до 100%). Это свойство не только этой серии, но и всех серий родительской группы серий. Это проекция соответствующего свойства в родительской группе серий, и поэтому это свойство только для чтения. Чтобы изменить значение, используйте свойство ParentSeriesGroup.Overlap для чтения/записи. Только для чтения SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | Представляет макет родительских категорий меток. Применяется только к диаграммам Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | Возвращает родительскую группу серий. Только для чтения [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | Указывает, как определить, какие точки данных находятся во втором круге или баре на диаграмме кругов кругом или барами кругом. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.PieSplitBy для изменения значения. Только для чтения [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | Пользовательская информация о разделении для диаграммы "круг-круг" или "бар-бар" с пользовательским разделением. Содержит точки данных, которые должны быть отображены во втором круге или баре в диаграмме кругов кругом или барами кругом. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Только для чтения [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или баре на диаграмме кругов кругом или барами кругом. Используется вместе со свойством PieSplitBy. Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.PieSplitPosition для изменения значения. Только для чтения Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | Указывает, является ли эта серия построенной на второй оси значений. Чтение/запись Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | Представляет метод квартиля. Применяется только к диаграммам BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | Представляет элемент легенды, связанный с этой серией. Только для чтения [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | Указывает размер второго круга или бара диаграммы кругов кругом или барами кругом, в процентах от размера первого круга (может быть от 5 до 200 процентов). Это свойство не только этой серии, но и всех серий родительской группы серий - это проекция соответствующего свойства группы. Поэтому это свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.SecondPieSize для изменения значения. Только для чтения UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | Представляет соединительные линии. Применяется только к диаграммам Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | Представляет внутренние точки. True, если внутренние точки отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | Представляет средние маркеры. True, если средняя линия отображается на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | Представляет средние маркеры. True, если средние маркеры отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | Представляет выбросы. True, если выбросы отображаются на диаграмме BoxAndWhisker. Применяется только к диаграммам BoxAndWhisker. Чтение/запись Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | Представляет сглаживание кривой. True, если сглаживание кривой включено для линейной диаграммы или диаграммы разброса. Применяется только к линейным и разбросанным диаграммам, связанным линиями. Чтение/запись Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | Коллекция линейных трендов серии. Только для чтения [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | Возвращает тип этой серии. Чтение/запись [`ChartType`](../charttype). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | Возвращает автоматический цвет серии, основанный на индексе серии и стиле графика. Этот цвет используется по умолчанию, если FillType равен NotDefined. |

### См. также

* интерфейс [IChartComponent](../ichartcomponent)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->