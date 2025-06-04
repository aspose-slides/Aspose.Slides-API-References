---
title: Axis
second_title: Aspose.Sildes для .NET API Справочник
description: Инкапсулирует объект, представляющий ось графика.
type: docs
weight: 1100
url: /ru/aspose.slides.charts/axis/
---

## Класс Axis

Инкапсулирует объект, представляющий ось графика.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Свойства

| Название | Описание |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Указывает фактическую основную единицу оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Указывает фактический масштаб основной единицы оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Указывает фактическое максимальное значение на оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Указывает фактическую дополнительную единицу оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Указывает фактический масштаб дополнительной единицы оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Указывает фактическое минимальное значение на оси. Предварительно вызовите метод IChart.ValidateChartLayout() для получения фактического значения. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Представляет тип агрегирования оси категорий (разбиение на группы). Применяется к категориям. Используется только с сериями Histogram или HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применимо только к осям категорий и не применяется к 3-D графикам. Чтение/запись Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Указывает наименьшую единицу времени, представленную на оси даты. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Указывает ширину бинов, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Указывает тип оси категорий. Чтение/запись [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Возвращает родительский график. Только для чтения [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Представляет точку на оси, в которой перпендикулярная ось ее пересекает. Чтение/запись Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Представляет CrossType на указанной оси, где пересекается другая ось. Чтение/запись [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Указывает масштабное значение единиц отображения для оси значений. Чтение/запись [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Представляет формат оси. Только для чтения [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Определяет, имеет ли ось видимый заголовок. Чтение/запись Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Указывает, назначена ли основная единица оси автоматически. Чтение/запись Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Указывает, назначено ли максимальное значение автоматически. Чтение/запись Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Указывает, назначена ли дополнительная единица оси автоматически. Чтение/запись Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Указывает, назначено ли минимальное значение автоматически. Чтение/запись Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Указывает значение автоматического переполнения. Если false: используйте свойство OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Указывает значение автоматического интервала меток. Если false: используйте свойство TickLabelSpacing. Чтение/запись Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Указывает значение автоматического интервала делений. Если false: используйте свойство TickMarksSpacing. Чтение/запись Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Указывает значение автоматического недополнения. Если false: используйте свойство UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Указывает, является ли тип шкалы оси значений логарифмическим. Чтение/запись Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Указывает, связан ли формат с исходными данными. Чтение/запись Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Указывает, применяется ли переполнение. Используйте IsAutomaticOverflowBin и OverflowBin для регулировки значения переполнения. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Указывает, отображает ли MS PowerPoint данные от последнего к первому. Чтение/запись Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Указывает, применяется ли недополнение. Используйте IsAutomaticUnderflowBin и UnderflowBin для регулировки значения недополнения. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Указывает, видима ли ось. Чтение/запись Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Указывает расстояние меток от оси. Применяется к оси категорий или дат. Значение должно быть между 0% и 1000%. Чтение/запись UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Представляет логарифмическую основу. Значение по умолчанию - 10. Чтение/запись Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Представляет формат основных сеток на оси графика. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Представляет тип основных делений для указанной оси. Чтение/запись [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Представляет основные единицы для оси даты или значений. Чтение/запись Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Представляет масштаб основных единиц для оси даты. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Представляет максимальное значение на оси значений. Чтение/запись Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Представляет формат дополнительных сеток на оси графика. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Представляет тип дополнительных делений для указанной оси. Чтение/запись [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Представляет дополнительные единицы для оси даты или значений. Чтение/запись Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Представляет масштаб основных единиц для оси даты. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Представляет минимальное значение на оси значений. Чтение/запись Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Представляет строку формата для меток оси. Чтение/запись String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Указывает количество бинов, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Указывает на пользовательское значение переполнения. Применяется, когда свойство IsAutomaticOverflowBin установлено в false, а свойство IsOverflowBin равно true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Представляет положение оси. Чтение/запись [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Чтобы скрыть основные сетки, установите MajorGridLinesFormat.Line.FillFormat.FillType в FillType.NoFill. Только для чтения Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Чтобы скрыть дополнительные сетки, установите MinorGridLinesFormat.Line.FillFormat.FillType в FillType.NoFill. Только для чтения Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Представляет формат текста. Только для чтения [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Представляет положение меток делений на указанной оси. Чтение/запись [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Представляет угол вращения меток делений. Чтение/запись Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Указывает, сколько меток пропустить между нарисованной меткой. Применяется к оси категорий или серий. Чтение/запись UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Указывает, сколько делений следует пропустить перед тем, как нарисовать следующее. Применяется к оси категорий или серий. Чтение/запись UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Получает заголовок оси. Только для чтения [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Указывает на пользовательское значение недополнения. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false, а свойство IsUnderflowBin равно true. |

## Методы

| Название | Описание |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Устанавливает значение свойства IAxis.CategoryAxisType, которое автоматически определяется на основе данных оси. |

### Смотрите также

* класс [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* класс [AxesManager](../axesmanager)
* интерфейс [IAxis](../iaxis)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->