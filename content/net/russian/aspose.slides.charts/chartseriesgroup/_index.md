---
title: ChartSeriesGroup
second_title: Aspose.Sildes для .NET справочника API
description: Представляет группу серий.
type: docs
weight: 1460
url: /ru/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup класс

Represents group of series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Указывает, как значения размера пузырьков представлены на пузырьковой диаграмме. Чтение/запись [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Указывает коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). Чтение/запись Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Возвращает родительскую диаграмму. Только чтение [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 процентов от размера области построения). Чтение/запись Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Получает или задает угол первой части круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней позиции, от 0 до 360 градусов). Чтение/запись UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Возвращает или задает расстояние в процентах от ширины маркера между сериями данных в 3D-диаграмме. Чтение/запись UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Указывает пространство между кластерами столбцов или колонок в процентах от их ширины. Чтение/запись UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Истина, если у диаграммы есть линии серий. Применяется к сложенным столбчатым и диаграммам типа OfPie. Чтение/запись Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Указывает формат HiLowLines. HiLowLines применяется вместе с типами диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Указывает, насколько сильно столбцы и колонки перекрываются на двумерных диаграммах, в процентах (от -100% до 100%). - -100%: Максимальное расстояние (столбцы полностью разделены). - 0%: Столбцы расположены рядом без перекрытия и без промежутка. - 100%: Максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство поддерживает чтение/запись SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Указывает, как определять, какие точки данных находятся во второй части круговой или столбцовой диаграммы в диаграмме типа pie-of-pie или bar-of-pie. Чтение/запись [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Информация о пользовательском разбиении для диаграммы типа pie-of-pie или bar-of-pie с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во второй части круговой или столбцовой диаграммы. Только чтение [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое будет использовано для определения, какие точки данных находятся во второй части круговой или столбцовой диаграммы в диаграмме типа pie-of-pie или bar-of-pie. Используется вместе со свойством PieSplitBy. Чтение/запись Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Указывает, построены ли серии этой группы на вторичной оси. Только чтение Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Указывает размер второй части круговой или столбцовой диаграммы в диаграмме типа pie-of-pie или bar-of-pie в процентах от размера первой части (может быть от 5 до 200 процентов). Чтение/запись UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Возвращает коллекцию серий. Только чтение [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только чтение [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Обеспечивает доступ к верхним/нижним полосам линейных или биржевых диаграмм. Только чтение [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Примечания

1) Смотрите сводку и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («свойства группы серий»). «Свойства группы серий» в классе ChartSeriesGroup доступны для чтения и записи. Каждое из «свойств группы серий» может иметь лишь чтение-проекцию в классе ChartSeries.

### См. также

* интерфейс [IChartSeriesGroup](../ichartseriesgroup)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->