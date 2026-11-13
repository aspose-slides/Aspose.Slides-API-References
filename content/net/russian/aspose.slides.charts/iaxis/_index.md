---
title: IAxis
second_title: Aspose.Sildes для .NET API Reference
description: Инкапсулирует объект, представляющий ось диаграммы.
type: docs
weight: 1720
url: /ru/aspose.slides.charts/iaxis/
---
## IAxis интерфейс

Инкапсулирует объект, представляющий ось диаграммы.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Указывает фактическую основную единицу оси. Вызовите метод IChart.ValidateChartLayout() заранее, чтобы получить фактическое значение. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Указывает фактическую шкалу основной единицы оси. Вызовите метод IChart.ValidateChartLayout() заранее, чтобы получить фактическое значение. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Указывает фактическое максимальное значение на оси. Вызовите метод IChart.ValidateChartLayout() заранее, чтобы получить фактическое значение. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Указывает фактическую вспомогательную единицу оси. Вызовите метод IChart.ValidateChartLayout() заранее, чтобы получить фактическое значение. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Указывает фактическую шкалу вспомогательной единицы оси. Вызовите метод IChart.ValidateChartLayout() заранее, чтобы получить фактическое значение. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Указывает фактическое минимальное значение на оси. Вызовите метод IChart.ValidateChartLayout() заранее, чтобы получить фактическое значение. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Представляет тип агрегации категориальной оси (биннинг). Применяется к категории. Используется только с рядами Histogram или HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только для чтения [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к категориальным осям и не применяется к 3-D диаграммам. Чтение/запись Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Указывает наименьшую единицу времени, представляемую на оси даты. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Указывает ширину бина, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с рядами Histogram или HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Указывает тип категориальной оси. Чтение/запись [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Представляет точку на оси, где перпендикулярная ось её пересекает. Чтение/запись Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Представляет тип пересечения (CrossType) на указанной оси, где другая ось её пересекает. Чтение/запись [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Указывает значение масштабирования отображаемых единиц для оси значений. Чтение/запись [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Представляет формат оси. Только для чтения [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Определяет, имеет ли ось видимый заголовок. Чтение/запись Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Указывает, назначается ли основная единица оси автоматически. Чтение/запись Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Указывает, назначается ли максимальное значение автоматически. Чтение/запись Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Указывает, назначается ли вспомогательная единица оси автоматически. Чтение/запись Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Указывает, назначается ли минимальное значение автоматически. Чтение/запись Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Указывает автоматическое значение бина переполнения. Если false: используйте свойство OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Указывает автоматическое значение интервала меток делений. Если false: используйте свойство TickLabelSpacing. Чтение/запись Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Указывает автоматическое значение интервала отметок делений. Если false: используйте свойство TickMarksSpacing. Чтение/запись Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Указывает автоматическое значение бина недоборa (underflow). Если false: используйте свойство UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Указывает, является ли тип шкалы оси значений логарифмическим. Чтение/запись Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Указывает, связаны ли формат с исходными данными. Чтение/запись Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Указывает, применён ли бин переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения бина переполнения. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Указывает, отображает ли MS PowerPoint точки данных от последней к первой. Чтение/запись Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Указывает, применён ли бин недоборa. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения бина недоборa. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Указывает, видима ли ось. Чтение/запись Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Указывает расстояние меток от оси. Применяется к категориальной или датовой оси. Значение должно быть от 0 % до 1000 %. Чтение/запись UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Представляет логарифмическую основу. Значение по умолчанию — 10. Чтение/запись Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Представляет формат основных линий сетки на оси диаграммы. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Представляет тип основной отметки деления для указанной оси. Чтение/запись [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Представляет основные единицы для датовой или оси значений. Чтение/запись Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Представляет шкалу основной единицы для датовой оси. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Представляет максимальное значение на оси значений. Чтение/запись Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Представляет формат вспомогательных линий сетки на оси диаграммы. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Представляет тип вспомогательной отметки деления для указанной оси. Чтение/запись [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Представляет вспомогательные единицы для датовой или оси значений. Чтение/запись Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Представляет шкалу основной единицы для датовой оси. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Представляет минимальное значение на оси значений. Чтение/запись Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Представляет строку формата для подписей оси. Чтение/запись String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Указывает количество бинов, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с рядами Histogram или HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Указывает пользовательское значение бина переполнения. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Представляет положение оси. Чтение/запись [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Указывает, отображаются ли основные линии сетки. Только для чтения Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Указывает, отображаются ли вспомогательные линии сетки. Только для чтения Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Представляет положение подписей делений на указанной оси. Чтение/запись [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Представляет угол поворота подписей делений. Чтение/запись Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Указывает, сколько подписей делений пропускать между отрисовываемыми метками. Чтение/запись UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Указывает, сколько отметок делений следует пропустить перед следующей. Применяется к категориальной или оси серии. Чтение/запись UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Получает заголовок оси. Только для чтения [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Указывает пользовательское значение бина недоборa. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Устанавливает свойство IAxis.CategoryAxisType значением, автоматически определяемым на основе данных оси. |

### См. также

* интерфейс [IFormattedTextContainer](../iformattedtextcontainer)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->