---
title: ChartSeriesGroup
second_title: Aspose.Sildes для .NET API справка
description: Представляет группу серий.
type: docs
weight: 1470
url: /ru/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup класс

Представляет группу серий.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Свойства

| Name | Description |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Указывает, как значения размера пузыря отображаются на пузырчатой диаграмме. Чтение/запись [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Указывает коэффициент масштабирования для пузырчатой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). Чтение/запись Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Возвращает родительскую диаграмму. Только для чтения [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Указывает размер отверстия в кольцевой диаграмме (может быть от 0 до 90 процентов от размера области построения). Чтение/запись Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхнего положения, от 0 до 360 градусов). Чтение/запись UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Задает расстояние между данными серий в 3D-диаграмме в процентах от ширины маркера. Значение должно быть от 0 до 500. Чтение/запись UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Задает пространство между группами столбцов или колонок в процентах от их ширины. Значение должно быть от 0 до 500. Чтение/запись UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | True if chart has series lines. Applied to stacked bar и OfPie charts. Чтение/запись Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Указывает формат HiLowLines. HiLowLines применяются с типами диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Указывает, насколько столбцы и колонки перекрываются на 2-D-диаграммах, в процентах (от -100 % до 100 %). -100 %: максимальное расстояние (столбцы полностью разделены). 0 %: столбцы расположены рядом без перекрытия и без промежутков. 100 %: максимальное перекрытие (столбцы полностью накладываются друг на друга). Это свойство является чтение/запись SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Указывает, как определять, какие точки данных находятся во втором секторе или столбце в диаграммах pie-of-pie или bar-of-pie. Чтение/запись [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Пользовательская информация о разбиении для диаграммы pie-of-pie или bar-of-pie с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором секторе или столбце. Только для чтения [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое используется для определения, какие точки данных находятся во втором секторе или столбце в диаграммах pie-of-pie или bar-of-pie. Используется совместно со свойством PieSplitBy. Чтение/запись Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Указывает, построена ли серия этой группы по вторичной оси. Только для чтения Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Указывает размер второго сектора или столбца в диаграмме pie-of-pie или bar-of-pie в процентах от размера первого сектора (может быть от 5 до 200 процентов). Чтение/запись UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Возвращает коллекцию серий. Только для чтения [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только для чтения [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Предоставляет доступ к верхним/нижним столбцам линейной или сточной диаграммы. Только для чтения [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Примечания

1) См. сводку и примечания к классу ChartSeriesGroupCollection и перечислению CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («series group properties»). «Series group properties» в классе ChartSeriesGroup является чтение/запись. Каждое из «series group properties» может иметь только для чтения проекцию в классе ChartSeries.

### См. также

* интерфейс [IChartSeriesGroup](../ichartseriesgroup)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->