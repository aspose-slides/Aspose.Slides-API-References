---
title: IChartSeriesGroup
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет группу серий.
type: docs
weight: 1810
url: /ru/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup interface

Представляет группу серий.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Позволяет получить базовый интерфейс IChartComponent. Только для чтения[`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Указывает, как значения размера пузырьков представлены на пузырьковой диаграмме. Чтение/запись[`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Определяет коэффициент масштабирования для пузырьковой диаграммы (может быть от 0 до 300 процентов размера по умолчанию). Чтение/записьInt32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Задает размер отверстия в кольцевой диаграмме (может составлять от 10 до 90 процентов от размера области графика). Чтение/записьByte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Получает или задает угол первого фрагмента круговой или кольцевой диаграммы, в градусах (по часовой стрелке сверху, от 0 до 360 градусов). Чтение/записьUInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Возвращает или задает расстояние в процентах от ширины маркера между рядами данных на трехмерной диаграмме. Чтение/записьUInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Задает расстояние между кластерами полос или столбцов в процентах от ширины полосы или столбца. Чтение/записьUInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | Истинно, если на диаграмме есть линии серий. Применяется к линейчатым диаграммам с накоплением и круговым диаграммам. Чтение/записьBoolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Задает формат HiLowLines. HiLowLines применяется с типами диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в серии имеет свой цвет. Чтение/записьBoolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Указывает, сколько полос и столбцов должно перекрываться на двумерных диаграммах (от -100 до 100). Чтение/записьSByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Указывает, как определить, какие точки данных находятся во второй круговой диаграмме или столбце на круговой или столбчатой диаграмме . Чтение/запись[`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Пользовательская информация о разделении для круговой или столбчатой диаграммы с пользовательским разделением. Содержит точки данных, которые должны быть отображены во второй круговой диаграмме или столбце в круговой или столбчатой диаграмме. Только для чтения[`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое должно использоваться для определения того, какие точки данных находятся во втором круге или столбце на круге или столбце круговая диаграмма. Используется вместе со свойством PieSplitBy. Чтение/записьDouble. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Указывает, нанесен ли ряд этой группы на второстепенную ось. Только чтениеBoolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Задает размер второй круговой диаграммы или столбца круговой диаграммы или столбчатой диаграммы в виде процент от размера первого круга (может быть от 5 до 200 процентов). Чтение/записьUInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Возвращает доступную только для чтения коллекцию серий диаграмм. Только для чтения[`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только для чтения[`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Предоставляет доступ к барам вверх/вниз линейного или биржевого графика. Только для чтения[`IUpDownBarsManager`](../iupdownbarsmanager). |

### Примечания

1) См. сводку и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, которые являются общими для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup доступны для чтения/записи. Каждое из "свойств группы серий" может иметь доступную только для чтения проекцию в классе ChartSeries.

### Смотрите также

* interface [IChartComponent](../ichartcomponent)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
