---
title: IAxis
second_title: Aspose.Sildes для .NET API Reference
description: Инкапсулирует объект, представляющий ось графика.
type: docs
weight: 1630
url: /ru/aspose.slides.charts/iaxis/
---

## Интерфейс IAxis

Инкапсулирует объект, представляющий ось графика.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Указывает фактическую основную единицу оси. Вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Указывает фактическую шкалу основных единиц оси. Вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Указывает фактическое максимальное значение на оси. Вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Указывает фактическую второстепенную единицу оси. Вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Указывает фактическую шкалу второстепенных единиц оси. Вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Указывает фактическое минимальное значение на оси. Вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Представляет тип агрегации категориальной оси (бинирование). Применяется к категории. Используется только с сериями Histogram или HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только для чтения [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Представляет, пересекает ли ось значений категориальную ось между категориями. Это свойство применяется только к категориальным осям и не применяется к 3-D графикам. Читаемое/записываемое логическое значение. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Указывает наименьшую временную единицу, представленную на оси дат. Читаемое/записываемое [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Указывает ширину бина, когда значение свойства AggregationType установлено на AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Указывает тип категориальной оси. Читаемое/записываемое [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Представляет точку на оси, где перпендикулярная ось ее пересекает. Читаемое/записываемое значение типа Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Представляет CrossType на указанной оси, где пересекается другая ось. Читаемое/записываемое [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Указывает значение масштабирования отображаемых единиц для оси значений. Читаемое/записываемое [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Представляет формат оси. Только для чтения [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Определяет, имеет ли ось видимый заголовок. Читаемое/записываемое логическое значение. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Указывает, присвоена ли основная единица оси автоматически. Читаемое/записываемое логическое значение. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Указывает, присвоено ли максимальное значение автоматически. Читаемое/записываемое логическое значение. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Указывает, присвоена ли второстепенная единица оси автоматически. Читаемое/записываемое логическое значение. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Указывает, присвоено ли минимальное значение автоматически. Читаемое/записываемое логическое значение. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Указывает значение автоматического бина переполнения. Если значение false: используйте свойство OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Указывает значение автоматического интервала меток делений. Если значение false: используйте свойство TickLabelSpacing. Читаемое/записываемое логическое значение. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Указывает значение автоматического интервала меток. Если значение false: используйте свойство TickMarksSpacing. Читаемое/записываемое логическое значение. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Указывает значение автоматического бина недополнения. Если значение false: используйте свойство UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Представляет, является ли тип шкалы оси значений логарифмическим. Читаемое/записываемое логическое значение. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Указывает, связан ли формат с исходными данными. Читаемое/записываемое логическое значение. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Указывает, применяется ли бин переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения бина переполнения. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Представляет, строит ли MS PowerPoint точки данных с конца к началу. Читаемое/записываемое логическое значение. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Указывает, применяется ли бин недополнения. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения бина недополнения. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Представляет, видима ли ось. Читаемое/записываемое логическое значение. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Указывает расстояние меток от оси. Применяется к категориальной или временной оси. Значение должно быть между 0% и 1000%. Читаемое/записываемое UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Представляет логарифмическую основу. Значение по умолчанию - 10. Читаемое/записываемое Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Представляет формат основных сеточных линий на оси графика. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Представляет тип основных делений для указанной оси. Читаемое/записываемое [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Представляет основные единицы для оси дат или значений. Читаемое/записываемое Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Представляет шкалу основных единиц для оси дат. Читаемое/записываемое [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Представляет максимальное значение на оси значений. Читаемое/записываемое Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Представляет формат второстепенных сеточных линий на оси графика. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Представляет тип второстепенных делений для указанной оси. Читаемое/записываемое [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Представляет второстепенные единицы для оси дат или значений. Читаемое/записываемое Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Представляет шкалу второстепенных единиц для оси дат. Читаемое/записываемое [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Представляет минимальное значение на оси значений. Читаемое/записываемое Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Представляет строку формата для меток оси. Читаемое/записываемое String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Указывает количество бинов, когда значение свойства AggregationType установлено на AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с сериями Histogram или HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Указывает пользовательское значение бина переполнения. Применяется, когда значение свойства IsAutomaticOverflowBin установлено в false и значение свойства IsOverflowBin равно true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Представляет положение оси. Читаемое/записываемое [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Представляет, показываются ли основные сеточные линии. Только для чтения логическое значение. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Представляет, показываются ли второстепенные сеточные линии. Только для чтения логическое значение. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Представляет положение меток делений на указанной оси. Читаемое/записываемое [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Представляет угол поворота меток делений. Читаемое/записываемое значение типа Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Указывает, сколько меток делений следует пропустить между нарисованной меткой. Читаемое/записываемое UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Указывает, сколько меток делений следует пропустить перед тем, как нарисовать следующую. Применяется к категориальным или сериям осей. Читаемое/записываемое UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Получает заголовок оси. Только для чтения [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Указывает пользовательское значение бина недополнения. Применяется, когда значение свойства IsAutomaticUnderflowBin установлено в false и значение свойства IsUnderflowBin равно true. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Устанавливает свойство IAxis.CategoryAxisType со значением, которое автоматически определяется на основе данных оси. |

### Смотрите также

* интерфейс [IFormattedTextContainer](../iformattedtextcontainer)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->