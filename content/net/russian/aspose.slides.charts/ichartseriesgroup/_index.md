---
title: IChartSeriesGroup
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет группу серий.
type: docs
weight: 1870
url: /ru/aspose.slides.charts/ichartseriesgroup/
---

## IChartSeriesGroup интерфейс

Представляет группу серий.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Свойства

| Название | Описание |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Позволяет получить базовый интерфейс IChartComponent. Только для чтения [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Указывает, как значения размеров пузырей представлены на пузырьковой диаграмме. Чтение/запись [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Указывает коэффициент масштаба для пузырьковой диаграммы (может быть между 0 и 300 процентами от заданного размера). Чтение/запись Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Указывает размер отверстия в кольцевой диаграмме (может быть между 10 и 90 процентами от размера области построения). Чтение/запись Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Получает или устанавливает угол первого сегмента круговой или кольцевой диаграммы в градусах (по часовой стрелке, начиная сверху, от 0 до 360 градусов). Чтение/запись UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Возвращает или устанавливает расстояние, в процентах от ширины маркера, между серией данных на 3D-диаграмме. Чтение/запись UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Указывает пространство между группами столбцов или баров, в процентах от ширины столбца или бара. Чтение/запись UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True, если диаграмма имеет линии серий. Применяется к накопленным столбчатым и круговым диаграммам. Чтение/запись Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Указывает формат HiLowLines. HiLowLines применяются с HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose типами диаграмм. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в серии имеет разные цвета. Чтение/запись Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Указывает, на сколько бары и столбцы должны перекрывать друг друга на 2D-диаграммах, в процентах (от -100% до 100%). - -100%: Максимальное разделение (бары полностью разделены). - 0%: Бары размещены рядом друг с другом без перекрытия или промежутков. - 100%: Максимальное перекрытие (бары полностью накладываются друг на друга). Это свойство доступно для чтения/записи SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Указывает, как определить, какие точки данных находятся во втором круге или баре на круговой диаграмме. Чтение/запись [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Пользовательская информация о разбиении для круговой диаграммы с пользовательским разбиением. Содержит точки данных, которые должны отображаться во втором круге или баре на круговой диаграмме. Только для чтения [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во втором круге или баре на круговой диаграмме. Используется вместе со свойством PieSplitBy. Чтение/запись Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Указывает, если серия этой группы отображается на вторичной оси. Только для чтения Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Указывает размер второго круга или бара на круговой диаграмме, в процентах от размера первого круга (может быть между 5 и 200 процентами). Чтение/запись UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Возвращает только для чтения коллекцию серий диаграммы. Только для чтения [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только для чтения [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Предоставляет доступ к восходящим/нисходящим барам линейной или фондовой диаграммы. Только для чтения [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Заметки

1) См. сводку и замечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, которые являются общими для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup доступны для чтения/записи. Каждое из "свойств группы серий" может иметь только для чтения проекцию в классе ChartSeries.

### Смотрите также

* интерфейс [IChartComponent](../ichartcomponent)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->