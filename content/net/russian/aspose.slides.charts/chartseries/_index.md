---
title: ChartSeries
second_title: Aspose.Sildes для .NET API Reference
description: Представляет собой серию графиков.
type: docs
weight: 1360
url: /ru/aspose.slides.charts/chartseries/
---

## Класс ChartSeries

Представляет собой серию графиков.

```csharp
public class ChartSeries : IChartSeries
```

## Свойства

| Название | Описание |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Указывает форму серии трехмерного столбчатого графика. Изменение значения этого свойства может привести к автоматическому изменению типа серии. Чтение/запись [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Указывает, как значения размера пузырьков представляются на пузырьковом графике. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.BubbleSizeRepresentation для изменения значения. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Указывает масштабный коэффициент для пузырькового графика (может быть от 0 до 300 процентов от размера по умолчанию). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.BubbleSizeScale для изменения значения. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Возвращает родительский график. Только для чтения [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Возвращает коллекцию точек данных этой серии. Только для чтения [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Указывает размер отверстия в кольцевом графике (может быть от 10 до 90 процентов от размера области графика). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.DoughnutHoleSize для изменения значения. Только для чтения Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Представляет ErrorBars серии с направлением X. ErrorBars с направлением X доступны для серий типа area, bar, scatter и bubble. Для любых других типов графиков это свойство возвращает null (включая 3D-графики). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (свойство [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Только для чтения [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Представляет ErrorBars серии с направлением Y. ErrorBars с направлением Y доступны для серий типа area, bar, line, scatter и bubble. Для любых других типов графиков это свойство возвращает null (включая 3D-графики). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (свойство [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Только для чтения [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Расстояние открытого сегмента пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. Чтение/запись Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Указывает угол первого сегмента круговой или кольцевой диаграммы, в градусах (по часовой стрелке сверху, от 0 до 360 градусов). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.FirstSliceAngle для изменения значения. Только для чтения UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Возвращает формат серии. Только для чтения [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Возвращает или устанавливает расстояние, в процентах от ширины маркера, между сериями данных в 3D-графике. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.GapDepth для изменения значения. Только для чтения Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Указывает пространство между группами столбцов или столбиков, в процентах от ширины столбца или столбика. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.GapWidth для изменения значения. Только для чтения Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Определяет, существуют ли линии серий для этой серии и смежных серий. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.HasSeriesLines для изменения значения. Используйте свойство ParentSeriesGroup.SeriesLinesFormat для форматирования линий серий. Только для чтения Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Определяет, имеет ли линейный или фондовый график бары вверх/вниз. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.UpDownBars.HasUpDownBars для изменения значения. Используйте свойство ParentSeriesGroup.UpDownBars для форматирования баров вверх/вниз. Только для чтения Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Указывает инвертированный сплошной цвет для серии. Чтобы применить настройки цвета, установите формат серии в FillType.Solid. Чтение/запись [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Указывает, должна ли серия столбиков, столбцов или пузырьков инвертировать свои цвета, если значение отрицательное. Чтение/запись Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Указывает, что каждый маркер данных в серии имеет разный цвет. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.IsColorVaried для изменения значения. Только для чтения Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Возвращает метки серии. Только для чтения [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Маркер. Только для чтения [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Возвращает имя серии. Только для чтения [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | Формат числа размеров пузырьков. Чтение/запись String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | Формат числа значений. Чтение/запись String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | Формат числа X значений. Чтение/запись String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | Формат числа Y значений. Чтение/запись String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Возвращает порядок серии. Чтение/запись Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Указывает, насколько столбцы и бары перекрываются на 2D-графиках, в процентах (от -100% до 100%). Это свойство касается не только этой серии, но и всех серий родительской группы. Это проекция соответствующего свойства в родительской группе серий, и поэтому это свойство является только для чтения. Чтобы изменить значение, используйте свойство !:ParentSeriesGroup.Overlap для чтения/записи. Только для чтения SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Представляет макет меток родительской категории. Применяется только к графикам Treemap. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | Родительская группа серий. Только для чтения [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Указывает, как определить, какие точки данных находятся во втором круге или баре на круговой диаграмме или баре круговой диаграммы. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.PieSplitBy для изменения значения. Только для чтения [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Кастомная информация о разделении для круговой диаграммы с пользовательским разделением. Содержит точки данных, которые должны быть изображены во втором круге или баре на круговой диаграмме или баре круговой диаграммы. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Только для чтения [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Указывает значение, которое должно быть использовано для определения, какие точки данных находятся во втором круге или баре на круговой диаграмме или баре круговой диаграммы. Используется вместе с свойством PieSplitBy. Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.PieSplitPosition для изменения значения. Только для чтения Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Указывает, если эта серия изображена на вторичной оси. Чтение/запись Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Представляет метод квартилей. Применяется только к графикам BoxAndWhisker. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Представляет запись легенды, связанную с этой серией. Только для чтения [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Указывает размер второго круга или бара круговой диаграммы с кругом круговой диаграммы, в процентах от размера первого круга (может быть от 5 до 200 процентов). Это свойство относится не только к этой серии, но и ко всем сериям родительской группы - это проекция соответствующего свойства группы. Поэтому это свойство является только для чтения. Используйте свойство ParentSeriesGroup для доступа к родительской группе серий. Используйте свойство ParentSeriesGroup.SecondPieSize для изменения значения. Только для чтения UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Представляет соединительные линии. Применяется только к графикам Waterfall. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Представляет внутренние точки. True, если внутренние точки показываются на графике BoxAndWhisker. Применяется только к графикам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Представляет среднюю линию. True, если средняя линия показывается на графике BoxAndWhisker. Применяется только к графикам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Представляет маркеры среднего. True, если маркеры среднего показываются на графике BoxAndWhisker. Применяется только к графикам BoxAndWhisker. Чтение/запись Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Представляет выбросы. True, если выбросы показываются на графике BoxAndWhisker. Применяется только к графикам BoxAndWhisker. Чтение/запись Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Представляет сглаживание кривой. True, если сглаживание кривой включено для линейного графика или графика разброса. Применяется только к линейным и разбросанным графикам, соединенным линиями. Чтение/запись Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Коллекция трендовых линий серии. Только для чтения [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Возвращает тип этой серии. Чтение/запись [`ChartType`](../charttype). |

## Методы

| Название | Описание |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Возвращает автоматический цвет серии на основе индекса серии и стиля графика. Этот цвет используется по умолчанию, если FillType равен NotDefined. |

### Смотрите также

* интерфейс [IChartSeries](../ichartseries)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->