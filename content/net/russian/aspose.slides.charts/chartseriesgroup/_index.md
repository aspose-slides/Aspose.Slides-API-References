---
title: ChartSeriesGroup
second_title: Aspose.Sildes для .NET API Reference
description: Представляет группу серий.
type: docs
weight: 1380
url: /ru/aspose.slides.charts/chartseriesgroup/
---

## Класс ChartSeriesGroup

Представляет группу серий.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## Свойства

| Название | Описание |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | Определяет, как значения размеров пузырьков представлены на пузырьковом графике. Чтение/запись [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | Указывает коэффициент масштабирования для пузырькового графика (может быть от 0 до 300 процентов от размера по умолчанию). Чтение/запись Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | Возвращает родительский график. Только для чтения [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | Указывает размер отверстия в кольцевом графике (может быть от 0 до 90 процентов от размера области построения). Чтение/запись Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | Получает или задает угол первого сегмента круговой или кольцевой диаграммы в градусах (по часовой стрелке от вверх, от 0 до 360 градусов). Чтение/запись UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | Возвращает или устанавливает расстояние как процент ширины маркера между рядами данных на 3D-графике. Чтение/запись UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | Указывает пространство между группами столбцов или баров как процент ширины столбца или бруса. Чтение/запись UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | Истина, если график имеет линии серий. Применяется к сложенным столбцам и диаграммам "Из нескольких частей". Чтение/запись Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | Указывает формат линий HiLow. Линии HiLow применяются с типами графиков HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в серии имеет разный цвет. Чтение/запись Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | Указывает, на сколько столбцы и бары должны перекрываться на 2-D графиках, в процентах (от -100% до 100%). - -100%: Максимальное расстояние (столбцы полностью разнесены). - 0%: Столбцы находятся рядом без пересечения или расстояния. - 100%: Максимальное перекрытие (столбцы полностью перекрывают друг друга). Это свойство является читаемым/записываемым SByte. |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | Указывает, как определить, какие точки данных находятся во втором пироге или баре на диаграмме "Круговой из круговой" или "Столбце из столбца". Чтение/запись [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | Информация о пользовательском разделении для диаграммы "Круговой из круговой" или "Столбце из столбца" с пользовательским разделением. Содержит точки данных, которые должны быть нарисованы во втором пироге или баре на диаграмме "Круговой из круговой" или "Столбце из столбца". Только для чтения [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое должно быть использовано для определения, какие точки данных находятся во втором пироге или баре на диаграмме "Круговой из круговой" или "Столбце из столбца". Используется вместе со свойством PieSplitBy. Чтение/запись Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | Указывает, если серии этой группы нарисованы на вторичной оси. Только для чтения Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | Указывает размер второго пирога или бара диаграммы "Круговой из круговой" или "Столбец из столбца" в процентах от размера первого пирога (может быть от 5 до 200 процентов). Чтение/запись UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | Возвращает коллекцию серий. Только для чтения [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | Возвращает тип этой группы серий. Только для чтения [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Предоставляет доступ к барам "вверх/вниз" графика линии или акций. Только для чтения [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Замечания

1) См. аннотацию и замечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа серий содержит некоторые свойства серий, которые являются общими для каждой серии в группе ("свойства группы серий"). "Свойства группы серий" в классе ChartSeriesGroup имеют возможность чтения/записи. Каждое из "свойств группы серий" может иметь только для чтения проекцию в классе ChartSeries.

### См. также

* интерфейс [IChartSeriesGroup](../ichartseriesgroup)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->