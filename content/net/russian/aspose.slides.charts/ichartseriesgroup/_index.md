---
title: IChartSeriesGroup
second_title: Aspose.Sildes для .NET Справка API
description: Представляет группу рядов.
type: docs
weight: 1970
url: /ru/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup интерфейс

Представляет группу рядов.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | Позволяет получить базовый интерфейс IChartComponent. Только для чтения [`IChartComponent`](../ichartcomponent). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | Указывает, как значения размера пузырей отображаются на пузырчатой диаграмме. Чтение/запись [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | Указывает коэффициент масштабирования для пузырчатой диаграммы (может быть от 0 до 300 процентов от размера по умолчанию). Чтение/запись Int32. |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | Указывает размер отверстия в кольцевой диаграмме (может быть от 10 до 90 процентов от размера области построения). Чтение/запись Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | Получает или задает угол первой дольки круговой или кольцевой диаграммы в градусах (по часовой стрелке от верхней позиции, от 0 до 360 градусов). Чтение/запись UInt16. |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | Получает или задает расстояние между рядами данных в 3D-диаграмме в процентах от ширины маркера. Значение должно быть от 0 до 500. Чтение/запись UInt16. |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | Получает или задает пространство между кластерами столбцов или колонок в процентах от их ширины. Значение должно быть от 0 до 500. Чтение/запись UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | True, если в диаграмме есть линии рядов. Применяется к сложенным столбчатым и OfPie диаграммам. Чтение/запись Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | Указывает формат HiLowLines. HiLowLines применяется к типам диаграмм HiLowClose, OpenHiLowClose, VolumeHiLowClose и VolumeOpenHiLowClose. |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | Указывает, что каждый маркер данных в ряду имеет различный цвет. Чтение/запись Boolean. |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | Получает элемент по указанному индексу. |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | Указывает, насколько столбцы и колонны должны перекрываться на 2-D диаграммах, в процентах (от -100% до 100%). -100%: Максимальное расстояние (столбцы полностью отделены). 0%: Столбцы расположены рядом без перекрытия и без промежутков. 100%: Максимальное перекрытие (столбцы полностью перекрывают друг друга). Это свойство читается/записывается SByte. |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | Указывает, как определить, какие точки данных находятся во второй круге или столбце на диаграмме pie-of-pie или bar-of-pie. Чтение/запись [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | Пользовательская информация о разбиении для диаграммы pie-of-pie или bar-of-pie с пользовательским разбиением. Содержит точки данных, которые должны быть отрисованы во втором круге или столбце на диаграмме pie-of-pie или bar-of-pie. Только для чтения [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | Указывает значение, которое будет использоваться для определения, какие точки данных находятся во второй круге или столбце на диаграмме pie-of-pie или bar-of-pie. Используется вместе со свойством PieSplitBy. Чтение/запись Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | Указывает, построены ли ряды этой группы на вторичной оси. Только для чтения Boolean. |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | Указывает размер второго круга или столбца на диаграмме pie-of-pie или bar-of-pie в процентах от размера первого круга (может быть от 5 до 200 процентов). Чтение/запись UInt16. |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | Возвращает только для чтения коллекцию рядов диаграммы. Только для чтения [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | Возвращает тип этой группы рядов. Только для чтения [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Обеспечивает доступ к верхним/нижним столбцам линейной или биржевой диаграммы. Только для чтения [`IUpDownBarsManager`](../iupdownbarsmanager). |

### Примечания

1) См. сводку и примечания для класса ChartSeriesGroupCollection и перечисления CombinableSeriesTypesGroup. 2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе ("свойства группы рядов"). "Свойства группы рядов" в классе ChartSeriesGroup являются читаемыми/записываемыми. Каждое из "свойств группы рядов" может иметь только для чтения проекцию в классе ChartSeries.

### Смотрите также

* интерфейс [IChartComponent](../ichartcomponent)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->