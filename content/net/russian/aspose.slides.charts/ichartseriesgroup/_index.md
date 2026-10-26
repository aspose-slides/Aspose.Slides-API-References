---
title: IChartSeriesGroup
second_title: Aspose.Sildes для .NET справочник API
description: Представляет группу серий.
type: docs
weight: 1950
url: /ru/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup интерфейс

Представляет группу серий.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Свойства

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Позволяет получить базовый интерфейс IChartComponent. Только для чтения [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Определяет, как значения размеров пузырей отображаются на пузырьковой диаграмме. Чтение/запись [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Определяет коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 percents of the default size). Чтение/запись Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Определяет размер отверстия в кольцевой диаграмме (может быть от 10 до 90 percents of the size of the plot area.). Чтение/запись Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Получает или задает угол первого сектора круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней, от 0 до 360 градусов). Чтение/запись UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Возвращает или задает расстояние, как процент от ширины маркера, между сериями данных в 3D-диаграмме. Чтение/запись UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Определяет промежуток между кластерами полос или столбцов, как процент от их ширины. Чтение/запись UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True, если диаграмма имеет линии серии. Применяется к stacked bar и OfPie диаграммам. Чтение/запись Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Определяет формат HiLowLines. HiLowLines применяется с типами диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Определяет, что каждый маркер данных в серии имеет разный цвет. Чтение/запись Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Определяет, насколько полосы и столбцы должны перекрываться на 2-D диаграммах, как процент (от -100% до 100%). -100%: Максимальное разspacing (полосы полностью разделены). -0%: Полосы расположены рядом без перекрытия или промежутка. 100%: Максимальное перекрытие (полосы полностью перекрывают друг друга). Это свойство — чтение/запись SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Определяет, как определить, какие точки данных находятся во второй части диаграммы типа pie-of-pie или bar-of-pie. Чтение/запись [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Информация о пользовательском разделении для диаграммы типа pie-of-pie или bar-of-pie с пользовательским разделением. Содержит точки данных, которые должны быть отрисованы во второй части диаграммы типа pie-of-pie или bar-of-pie. Только для чтения [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Определяет значение, которое будет использовано для определения, какие точки данных находятся во второй части диаграммы типа pie-of-pie или bar-of-pie. Используется совместно со свойством PieSplitBy. Чтение/запись Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Указывает, отображаются ли серии этой группы на вторичной оси. Только для чтения Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Определяет размер второй части круговой или столбчатой диаграммы типа pie-of-pie или bar-of-pie в процентах от размера первой части (может быть от 5 до 200 percents). Чтение/запись UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Возвращает только для чтения коллекцию серий диаграммы. Только для чтения [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только для чтения [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Обеспечивает доступ к верхним/нижним полосам линейных или биржевых диаграмм. Только для чтения [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Примечания

1) См. резюме и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («series group properties»). «Series group properties» в классе ChartSeriesGroup являются читаемыми/записываемыми. Каждое из «series group properties» может иметь только для чтения проекцию в классе ChartSeries.

### См. также

* интерфейс [IChartComponent](../ichartcomponent)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->