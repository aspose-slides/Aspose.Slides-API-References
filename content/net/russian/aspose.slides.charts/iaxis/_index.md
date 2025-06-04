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
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Указывает фактическую главную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Указывает фактическую шкалу главной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Указывает фактическое максимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Указывает фактическую меньшую единицу оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Указывает фактическую шкалу меньшей единицы оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Указывает фактическое минимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Представляет тип агрегации для категориальной оси (группировка). Применяется к категории. Используется только с графиками Гистограммы или HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только для чтения [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Представляет, пересекает ли ось значений категориальную ось между категориями. Это свойство применяется только к категориальным осям и не применяется к 3-D графикам. Чтение/запись Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Указывает наименьшую временную единицу, представляемую на оси даты. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Указывает ширину бинов, когда значение свойства AggregationType установлено на AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с графиками Гистограммы или HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Указывает тип категориальной оси. Чтение/запись [`CategoryAxisType`](./categoryaxistype). |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Представляет точку на оси, где перпендикулярная ось ее пересекает. Чтение/запись Single. |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Представляет CrossType на указанной оси, где пересекается другая ось. Чтение/запись [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Указывает масштабное значение отображаемых единиц для оси значений. Чтение/запись [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Представляет формат оси. Только для чтения [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Определяет, имеет ли ось видимый заголовок. Чтение/запись Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Указывает, назначена ли главная единица оси автоматически. Чтение/запись Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Указывает, назначено ли максимальное значение автоматически. Чтение/запись Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Указывает, назначена ли меньшая единица оси автоматически. Чтение/запись Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Указывает, назначено ли минимальное значение автоматически. Чтение/запись Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Указывает автоматическое значение переполненного бина. Если false: использовать свойство OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Указывает автоматическое значение расстояния между метками делений. Если false: использовать свойство TickLabelSpacing. Чтение/запись Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Указывает автоматическое значение расстояния между делениями. Если false: использовать свойство TickMarksSpacing. Чтение/запись Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Указывает автоматическое значение недополненного бина. Если false: использовать свойство UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Представляет, является ли тип шкалы оси значений логарифмическим или нет. Чтение/запись Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Указывает, связано ли форматирование с исходными данными. Чтение/запись Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Указывает, применяется ли переполненный бин. Используйте IsAutomaticOverflowBin и OverflowBin для корректировки значения переполненного бина. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Представляет, рисует ли MS PowerPoint точки данных с последней до первой. Чтение/запись Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Указывает, применяется ли недополненный бин. Используйте IsAutomaticUnderflowBin и UnderflowBin для корректировки значения недополненного бина. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Представляет, видима ли ось. Чтение/запись Boolean. |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Указывает расстояние меток от оси. Применяется к категориальным или временным осям. Значение должно быть между 0% и 1000%. Чтение/запись UInt16. |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Представляет логарифмическую основу. Значение по умолчанию 10. Чтение/запись Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Представляет формат основных сеточной линии на оси графика. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Представляет тип главной метки деления для указанной оси. Чтение/запись [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Представляет основные единицы для временной или значенческой оси. Чтение/запись Double. |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Представляет шкалу главной единицы для временной оси. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Представляет максимальное значение на оси значений. Чтение/запись Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Представляет формат меньших сеточных линий на оси графика. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Представляет тип меньшей метки деления для указанной оси. Чтение/запись [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Представляет меньшие единицы для временной или значенческой оси. Чтение/запись Double. |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Представляет шкалу главной единицы для временной оси. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Представляет минимальное значение на оси значений. Чтение/запись Double. |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Представляет строку формата для меток оси. Чтение/запись String. |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Указывает количество бинов, когда значение свойства AggregationType установлено на AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с графиками Гистограммы или HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Указывает настраиваемое значение переполненного бина. Применяется, когда свойство IsAutomaticOverflowBin установлено в false, а свойство IsOverflowBin равно true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Представляет позицию оси. Чтение/запись [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Представляет, отображаются ли основные сеточные линии. Только для чтения Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Представляет, отображаются ли меньшие сеточные линии. Только для чтения Boolean. |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Представляет положение меток делений на указанной оси. Чтение/запись [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Представляет угол поворота меток делений. Чтение/запись Single. |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Указывает, сколько меток делений пропустить между нарисованной меткой. Чтение/запись UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Указывает, сколько делений следует пропустить перед тем, как нарисовать следующее. Применяется к категориальным или сериям. Чтение/запись UInt16. |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Получает заголовок оси. Только для чтения [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Указывает настраиваемое значение недополненного бина. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false, а свойство IsUnderflowBin равно true. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Устанавливает свойство IAxis.CategoryAxisType значением, автоматически определяемым на основе данных оси. |

### Также см.
* интерфейс [IFormattedTextContainer](../iformattedtextcontainer)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: сгенерировано xmldocmd для Aspose.Slides.dll -->