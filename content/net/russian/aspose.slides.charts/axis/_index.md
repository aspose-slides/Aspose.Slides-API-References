---
title: Axis
second_title: Aspose.Sildes для .NET справочник API
description: Инкапсулирует объект, представляющий ось диаграммы.
type: docs
weight: 1180
url: /ru/aspose.slides.charts/axis/
---
## Axis класс

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Указывает фактическую основную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout() чтобы получить фактическое значение. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Указывает фактический масштаб основной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout() чтобы получить фактическое значение. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Указывает фактическое максимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout() чтобы получить фактическое значение. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Указывает фактическую вспомогательную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout() чтобы получить фактическое значение. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Указывает фактический масштаб вспомогательной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout() чтобы получить фактическое значение. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Указывает фактическое минимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout() чтобы получить фактическое значение. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Представляет тип агрегации категориальной оси (биннинг). Применяется к категории. Используется только с рядами Histogram или HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к категориальным осям и не применяется к 3-D диаграммам. Чтение/запись Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Указывает наименьшую единицу времени, представленную на оси даты. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Указывает ширину бина, когда значение свойства AggregationType установлено в AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с рядами Histogram или HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Указывает тип категориальной оси. Чтение/запись [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Возвращает родительскую диаграмму. Только чтение [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Представляет точку на оси, где перпендикулярная ось её пересекает. Чтение/запись Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Представляет тип пересечения (CrossType) на указанной оси, где она пересекает другую ось. Чтение/запись [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Указывает значение масштабирования отображаемых единиц для оси значений. Чтение/запись [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Представляет формат оси. Только чтение [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Определяет, имеет ли ось видимый заголовок. Чтение/запись Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Указывает, назначается ли основная единица оси автоматически. Чтение/запись Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Указывает, назначается ли максимальное значение автоматически. Чтение/запись Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Указывает, назначается ли вспомогательная единица оси автоматически. Чтение/запись Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Указывает, назначается ли минимальное значение автоматически. Чтение/запись Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Указывает автоматическое значение переполнения бина. Если false: используйте свойство OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Указывает автоматическое значение расстояния меток делений. Если false: используйте свойство TickLabelSpacing. Чтение/запись Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Указывает автоматическое значение расстояния меток делений. Если false: используйте свойство TickMarksSpacing. Чтение/запись Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Указывает автоматическое значение недоисполнения бина. Если false: используйте свойство UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Указывает, является ли тип шкалы оси значений логарифмическим. Чтение/запись Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Указывает, связана ли форматировка с исходными данными. Чтение/запись Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Указывает, применяется ли переполнение бина. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполнения бина. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Указывает, строит ли MS PowerPoint точки данных от последней к первой. Чтение/запись Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Указывает, применяется ли недоисполнение бина. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недоисполнения бина. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Указывает, видима ли ось. Чтение/запись Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Указывает расстояние меток от оси. Применяется к категориальной или датовой оси. Значение должно быть от 0% до 1000%. Чтение/запись UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Представляет логарифмическую основу. Значение по умолчанию — 10. Чтение/запись Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Представляет формат основных линий сетки на оси диаграммы. Только чтение [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Представляет тип основной метки деления для указанной оси. Чтение/запись [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Представляет основные единицы для датовой или оси значений. Чтение/запись Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Представляет масштаб основной единицы для датовой оси. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Представляет максимальное значение на оси значений. Чтение/запись Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Представляет формат вспомогательных линий сетки на оси диаграммы. Только чтение [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Представляет тип вспомогательной метки деления для указанной оси. Чтение/запись [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Представляет вспомогательные единицы для датовой или оси значений. Чтение/запись Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Представляет масштаб основной единицы для датовой оси. Чтение/запись [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Представляет минимальное значение на оси значений. Чтение/запись Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Представляет строку формата для меток оси (Axis Labels). Чтение/запись String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Указывает количество бинов, когда значение свойства AggregationType установлено в AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с рядами Histogram или HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Указывает пользовательское значение переполнения бина. Применяется, когда свойство IsAutomaticOverflowBin установлено в false и свойство IsOverflowBin равно true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Представляет позицию оси. Чтение/запись [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Чтобы скрыть основную линию сетки, установите MajorGridLinesFormat.Line.FillFormat.FillType в FillType.NoFill. Только чтение Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Чтобы скрыть вспомогательную линию сетки, установите MinorGridLinesFormat.Line.FillFormat.FillType в FillType.NoFill. Только чтение Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Представляет формат текста. Только чтение [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Представляет позицию меток делений на указанной оси. Чтение/запись [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Представляет угол поворота меток делений. Чтение/запись Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Указывает, сколько меток делений пропускать между отрисованными метками. Применяется к категориальной или оси серий. Чтение/запись UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Указывает, сколько меток делений пропускать перед следующей отрисовкой. Применяется к категориальной или оси серий. Чтение/запись UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Получает заголовок оси. Только чтение [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Указывает пользовательское значение недоисполнения бина. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false и свойство IsUnderflowBin равно true. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Устанавливает свойство IAxis.CategoryAxisType значением, автоматически определяемым на основе данных оси. |

### Смотрите также

* класс [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* класс [AxesManager](../axesmanager)
* интерфейс [IAxis](../iaxis)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->