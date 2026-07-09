---
title: ChartSeries
second_title: "Aspose.Sildes для .NET: справочник API"
description: Представляет ряд диаграммы.
type: docs
weight: 1440
url: /ru/aspose.slides.charts/chartseries/
---
## ChartSeries класс

Представляет ряд диаграммы.

```csharp
public class ChartSeries : IChartSeries
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | Определяет форму ряда 3-D столбчатой диаграммы. Изменение значения этого свойства может привести к автоматическому изменению типа ряда. Чтение/запись [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | Определяет, как значения размеров пузырей отображаются на пузырёчной диаграмме. Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.BubbleSizeRepresentation для чтения/записи значения. |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | Определяет коэффициент масштабирования пузырёчной диаграммы (может быть от 0 % до 300 % от размера по умолчанию). Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.BubbleSizeScale для чтения/записи значения. |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | Возвращает родительскую диаграмму. Только чтение [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | Возвращает коллекцию точек данных этого ряда. Только чтение [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | Определяет размер отверстия в кольцевой диаграмме (может быть от 10 % до 90 % от размера области построения). Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.DoughnutHoleSize для чтения/записи значения. Только чтение Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | Представляет ErrorBars ряда с направлением X. ErrorBars с направлением X доступны для рядов типов area, bar, scatter и bubble. Для остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с свойством [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Только чтение [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Представляет ErrorBars ряда с направлением Y. ErrorBars с направлением Y доступны для рядов типов area, bar, line, scatter и bubble. Для остальных типов диаграмм это свойство возвращает null (включая 3D-диаграммы). В случае пользовательских значений используйте коллекцию DataPoints для указания значения (с свойством [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues)). Только чтение [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | Расстояние открытого куска пирога от центра круговой диаграммы выражается в процентах от диаметра пирога. Чтение/запись Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | Определяет угол первого куска пирога или кольцевой диаграммы в градусах (по часовой стрелке от вертикали, от 0 до 360 градусов). Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.FirstSliceAngle для чтения/записи значения. Только чтение UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | Возвращает формат ряда. Только чтение [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | Возвращает или задаёт расстояние в процентах от ширины маркера между рядами данных в 3D-диаграмме. Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.GapDepth для чтения/записи значения. Только чтение Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | Определяет пространство между кластерами столбцов или колонок в процентах от их ширины. Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.GapWidth для чтения/записи значения. Только чтение Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | Определяет, присутствуют ли линии рядов для данного ряда и связанных рядов. Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.HasSeriesLines для чтения/записи значения. Для форматирования линий рядов используйте свойство ParentSeriesGroup.SeriesLinesFormat. Только чтение Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | Определяет, имеет ли линейная или стохастическая диаграмма верхние/нижние бары. Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.UpDownBars.HasUpDownBars для чтения/записи значения. Для форматирования верхних/нижних баров используйте свойство ParentSeriesGroup.UpDownBars. Только чтение Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | Указывает инвертированный сплошной цвет для ряда. Чтобы применить настройку цвета, задайте FillType формата ряда в FillType.Solid. Чтение/запись [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | Указывает, что столбцовый, колонный или пузырёчный ряд должен инвертировать свои цвета, если значение отрицательное. Чтение/запись Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | Указывает, что каждый маркер данных в ряду имеет различный цвет. Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.IsColorVaried для чтения/записи значения. Только чтение Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | Возвращает метки ряда. Только чтение [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Маркер. Только чтение [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | Возвращает имя ряда. Только чтение [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Чтение/запись String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Чтение/запись String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Чтение/запись String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Чтение/запись String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | Возвращает порядок ряда. Чтение/запись Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | Определяет, насколько столбцы и колонки перекрываются на 2-D диаграммах, в процентах (от -100 % до 100 %). Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда. Это проекция соответствующего свойства в группе родительского ряда, поэтому свойство только для чтения. Чтобы изменить значение, используйте свойство !:ParentSeriesGroup.Overlap для чтения/записи. Только чтение SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | Представляет расположение меток родительской категории. Применяется только к Treemap-диаграммам. |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Только чтение [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | Определяет способ определения, какие точки данных находятся во втором пироге или столбце диаграммы «pie-of-pie» или «bar-of-pie». Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.PieSplitBy для чтения/записи значения. Только чтение [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | Пользовательская информация о разбиении для диаграммы «pie-of-pie» или «bar-of-pie» с пользовательским разбиением. Содержит точки данных, которые должны быть нарисованы во втором пироге или столбце. Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Только чтение [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | Указывает значение, используемое для определения, какие точки данных находятся во втором пироге или столбце диаграммы «pie-of-pie» или «bar-of-pie». Используется совместно со свойством PieSplitBy. Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.PieSplitPosition для чтения/записи значения. Только чтение Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | Указывает, отображается ли этот ряд на вторичной оси. Чтение/запись Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | Представляет метод квартилей. Применяется только к BoxAndWhisker-диаграммам. |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | Представляет элемент легенды, связанный с этим рядом. Только чтение [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | Указывает размер второго пирога или столбца диаграммы «pie-of-pie» или «bar-of-pie» в процентах от размера первого пирога (может быть от 5 % до 200 %). Это свойство относится не только к данному ряду, но и ко всем рядам группы родительского ряда — это проекция соответствующего свойства группы. Поэтому свойство только для чтения. Используйте свойство ParentSeriesGroup для доступа к группе родительского ряда. Используйте свойство ParentSeriesGroup.SecondPieSize для чтения/записи значения. Только чтение UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | Представляет линии-соединители. Применяется только к Waterfall-диаграммам. |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | Представляет внутренние точки. true, если внутренние точки отображаются в BoxAndWhisker-диаграмме. Применяется только к BoxAndWhisker-диаграммам. Чтение/запись Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | Представляет среднюю линию. true, если средняя линия отображается в BoxAndWhisker-диаграмме. Применяется только к BoxAndWhisker-диаграммам. Чтение/запись Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | Представляет средние маркеры. true, если средние маркеры отображаются в BoxAndWhisker-диаграмме. Применяется только к BoxAndWhisker-диаграммам. Чтение/запись Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | Представляет выбросы. true, если выбросы отображаются в BoxAndWhisker-диаграмме. Применяется только к BoxAndWhisker-диаграммам. Чтение/запись Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | Представляет сглаживание кривой. true, если сглаживание включено для линейной или точечной диаграммы, соединенной линиями. Применяется только к линейным и точечным диаграммам, соединённым линиями. Чтение/запись Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | Коллекция линий тренда ряда. Только чтение [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | Возвращает тип этого ряда. Чтение/запись [`ChartType`](../charttype). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | Возвращает автоматический цвет ряда, основанный на индексе ряда и стиле диаграммы. Этот цвет используется по умолчанию, если FillType равен NotDefined. |

### См. также

* интерфейс [IChartSeries](../ichartseries)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->