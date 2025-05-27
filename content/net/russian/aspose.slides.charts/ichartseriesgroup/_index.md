---
title: IChartSeriesGroup
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет группу серий.
type: docs
weight: 1870
url: /ru/aspose.slides.charts/ichartseriesgroup/
---

## Интерфейс IChartSeriesGroup

Представляет группу серий.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Позволяет получить базовый интерфейс IChartComponent. Только для чтения [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Указывает, как значения размеров пузырей представлены на диаграмме пузырей. Чтение/запись [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Указывает коэффициент масштабирования для диаграммы пузырей (может быть от 0 до 300 процентов от размера по умолчанию). Чтение/запись Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера области построения). Чтение/запись Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Получает или задает угол первого сегмента круговой или кольцевой диаграммы, в градусах (по часовой стрелке от вверх, от 0 до 360 градусов). Чтение/запись UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Возвращает или устанавливает расстояние, как процент от ширины маркера, между рядами данных в 3D-диаграмме. Чтение/запись UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Указывает пространство между кластерами столбцов или баров, как процент от ширины столбца или бара. Чтение/запись UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True, если диаграмма имеет линию серий. Применяется к диаграммам со стековыми столбцами и с круговыми диаграммами. Чтение/запись Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Указывает формат HiLowLines. HiLowLines применяются с типами диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Указывает, на сколько бары и столбцы должны перекрываться на 2D-диаграммах, в процентах (от -100% до 100%). - -100%: Максимальное расстояние (бары полностью разделены). - 0%: Бары расположены рядом без перекрытия или расстояния. - 100%: Максимальное перекрытие (бары полностью перекрывают друг друга). Это свойство имеет тип чтения/записи SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Указывает, как определить, какие точки данных находятся во втором круге или баре на диаграмме круг-круг или бар-круг. Чтение/запись [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Пользовательская информация о разбиении для диаграммы круг-круг или бар-круг с пользовательским разбиением. Содержит точки данных, которые должны быть нарисованы во втором круге или баре в диаграмме круг-круг или бар-круг. Только для чтения [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое будет использоваться для определения того, какие точки данных находятся во втором круге или баре на диаграмме круг-круг или бар-круг. Используется вместе со свойством PieSplitBy. Чтение/запись Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Указывает, рисуется ли серия этой группы на вторичной оси. Только для чтения Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Указывает размер второго круга или бара диаграммы круг-круг или бар-круг, в процентах от размера первого круга (может быть от 5 до 200 процентов). Чтение/запись UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Возвращает только для чтения коллекцию серий диаграммы. Только для чтения [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только для чтения [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Предоставляет доступ к вверх/вниз барам для линейной или фондовой диаграммы. Только для чтения [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Примечания

1) См. резюме и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, которые общи для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup доступны для чтения/записи. Каждое из "свойств группы серий" может иметь проекцию только для чтения в классе ChartSeries.

### См. также

* интерфейс [IChartComponent](../ichartcomponent)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->