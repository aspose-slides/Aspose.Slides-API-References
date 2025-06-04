---
title: ChartSeriesGroup
second_title: Aspose.Sildes для .NET API Reference
description: Представляет группу серий.
type: docs
weight: 1380
url: /ru/aspose.slides.charts/chartseriesgroup/
---

## ChartSeriesGroup class

Представляет группу серий.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Properties

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Указывает, как значения размера пузырьков представляются на диаграмме с пузырьками. Чтение/запись [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Указывает коэффициент масштабирования для диаграммы с пузырьками (может быть между 0 и 300 процентами от размера по умолчанию). Чтение/запись Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Возвращает родительскую диаграмму. Только для чтения [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Указывает размер отверстия в круговой диаграмме (может быть между 0 и 90 процентами от размера области построения.). Чтение/запись Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Получает или задает угол первого кусочка круговой или кольцевой диаграммы в градусах (по часовой стрелке сверху, от 0 до 360 градусов). Чтение/запись UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Возвращает или задает расстояние, в процентах от ширины маркера, между сериями данных в 3D диаграмме. Чтение/запись UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Указывает пространство между группами столбиков или колонок, как процент от ширины столбика или колонки. Чтение/запись UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True, если диаграмма имеет линии серий. Применяется к сложенным столбчатым и круговым диаграммам. Чтение/запись Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Указывает формат HiLowLines. HiLowLines применяются к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в серии имеет другой цвет. Чтение/запись Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Указывает, насколько столбцы и колонки должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%). - -100%: Максимальное расстояние (столбцы полностью разделены). - 0%: Столбцы размещаются рядом друг с другом без перекрытия или расстояния. - 100%: Максимальное перекрытие (столбцы полностью перекрываются). Это свойство доступно для чтения/записи SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Указывает, как определить, какие точки данных находятся во втором круге или баре на диаграмме долька от дольки или бар от дольки. Чтение/запись [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Информация о пользовательской разбивке для диаграммы долька от дольки или бар от дольки с кастомной разбивкой. Содержит точки данных, которые должны быть нарисованы во втором круге или баре в диаграмме долька от дольки или бар от дольки. Только для чтения [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или баре на диаграмме долька от дольки или бар от дольки. Используется совместно со свойством PieSplitBy. Чтение/запись Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Указывает, откладывается ли серия этой группы на вторичную ось. Только для чтения Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Указывает размер второго круга или бара диаграммы долька от дольки или бар от дольки, как процент от размера первого круга (может быть между 5 и 200 процентами). Чтение/запись UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Возвращает коллекцию серий. Только для чтения [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только для чтения [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Приводит доступ к барам вверх/вниз диаграммы типа Line или Stock. Только для чтения [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Remarks

1) См. сводку и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, которые общие для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup доступны для чтения/записи. Каждое из "свойств группы серий" может иметь проекцию только для чтения в классе ChartSeries.

### See Also

* интерфейс [IChartSeriesGroup](../ichartseriesgroup)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->