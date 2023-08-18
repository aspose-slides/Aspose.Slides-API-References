---
title: ChartSeriesGroup
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет группу серий.
type: docs
weight: 1320
url: /ru/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup class

Представляет группу серий.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Указывает, как значения размера пузырьков представлены на пузырьковой диаграмме. Чтение/запись[`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Определяет коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов размера по умолчанию). Чтение/записьInt32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Возвращает родительскую диаграмму. Только для чтения[`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Задает размер отверстия в кольцевой диаграмме (может составлять от 0 до 90 процентов от размера области графика). Чтение/записьByte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Получает или задает угол первого фрагмента круговой или кольцевой диаграммы, в градусах (по часовой стрелке сверху, от 0 до 360 градусов). Чтение/записьUInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Возвращает или задает расстояние в процентах от ширины маркера между рядами данных на трехмерной диаграмме. Чтение/записьUInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Задает расстояние между кластерами полос или столбцов в процентах от ширины полосы или столбца. Чтение/записьUInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Истинно, если на диаграмме есть линии серий. Применяется к линейчатым диаграммам с накоплением и круговым диаграммам. Чтение/записьBoolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Задает формат HiLowLines. HiLowLines применяется с типами диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в серии имеет свой цвет. Чтение/записьBoolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Указывает, сколько полос и столбцов должно перекрываться на двумерных диаграммах (от -100 до 100). Чтение/записьSByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Указывает, как определить, какие точки данных находятся во второй круговой диаграмме или столбце на круговой или столбчатой диаграмме . Чтение/запись[`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Пользовательская информация о разделении для круговой или столбчатой диаграммы с пользовательским разделением. Содержит точки данных, которые должны быть отображены во второй круговой диаграмме или столбце в круговой или столбчатой диаграмме. Только для чтения[`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое должно использоваться для определения того, какие точки данных находятся во втором круге или столбце на круге или столбце круговая диаграмма. Используется вместе со свойством PieSplitBy. Чтение/записьDouble. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Указывает, нанесен ли ряд этой группы на второстепенную ось. Только чтениеBoolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Задает размер второй круговой диаграммы или столбца круговой диаграммы или столбчатой диаграммы в виде процент от размера первого круга (может быть от 5 до 200 процентов). Чтение/записьUInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Возвращает набор серий. Только для чтения[`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только для чтения[`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Предоставляет доступ к барам вверх/вниз линейного или биржевого графика. Только для чтения[`IUpDownBarsManager`](../iupdownbarsmanager). |

### Примечания

1) См. сводку и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, которые являются общими для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup доступны для чтения/записи. Каждое из "свойств группы серий" может иметь доступную только для чтения проекцию в классе ChartSeries.

### Смотрите также

* interface [IChartSeriesGroup](../ichartseriesgroup)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
