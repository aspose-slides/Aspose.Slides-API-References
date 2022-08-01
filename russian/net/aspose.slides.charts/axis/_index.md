---
title: Axis
second_title: Справочник по API Aspose.Slides для .NET
description: Инкапсулирует объект представляющий ось диаграммы.
type: docs
weight: 1040
url: /ru/net/aspose.slides.charts/axis/
---
## Axis class

Инкапсулирует объект, представляющий ось диаграммы.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Определяет фактическую основную единицу оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Задает фактический масштаб основных единиц оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Определяет фактическое максимальное значение на оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Определяет фактическую вспомогательную единицу оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Определяет фактический второстепенный масштаб оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Определяет фактическое минимальное значение на оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Представляет тип агрегации оси категорий (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к трехмерным диаграммам. Чтение/записьBoolean . |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Указывает наименьшую единицу времени, представленную на оси даты. Чтение/запись[`TimeUnitType`](../timeunittype) . |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Указывает ширину ячейки, когда для свойства AggregationType задано значение AxisAggregationType.ByBinWidth. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Определяет тип оси категорий. Чтение/запись[`CategoryAxisType`](../categoryaxistype) . |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Возвращает родительскую диаграмму. Только для чтения[`IChart`](../ichart) . |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Представляет точку на оси, где ее пересекает перпендикулярная ось. Чтение/записьSingle . |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Представляет CrossType на указанной оси, где пересекается другая ось. Чтение/запись[`CrossesType`](../crossestype) . |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Определяет значение масштабирования отображаемых единиц для оси значений. Чтение/запись[`DisplayUnitType`](../displayunittype) . |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Представляет формат оси. Только для чтения[`IAxisFormat`](../iaxisformat) . |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Определяет, имеет ли ось видимый заголовок. Чтение/записьBoolean . |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Указывает, назначается ли автоматически основная единица оси. Чтение/записьBoolean . |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Указывает, присваивается ли максимальное значение автоматически. Чтение/записьBoolean . |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Указывает, назначается ли автоматически младшая единица оси. Чтение/записьBoolean . |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Указывает, назначается ли минимальное значение автоматически. Чтение/записьBoolean . |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Определяет значение корзины автоматического переполнения. Если false: использовать свойство OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Задает значение автоматического интервала между метками деления. Если false: используйте свойство TickLabelSpacing. Чтение/записьBoolean . |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Определяет значение интервала автоматических делений. Если false: используйте свойство TickMarksSpacing. Чтение/записьBoolean . |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Определяет значение корзины для автоматического недополнения. Если false: использовать свойство UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Указывает, является ли тип шкалы оси значений логарифмическим или нет. Чтение/записьBoolean . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Указывает, является ли формат связанными исходными данными. Чтение/записьBoolean . |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Указывает, применяется ли бункер переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения корзины переполнения. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Указывает, отображает ли MS PowerPoint точки данных от последней к первой. Чтение/записьBoolean . |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Указывает, применяется ли бункер нижнего переполнения. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения корзины для недорасхода. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Указывает, видна ли ось. Чтение/записьBoolean . |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Определяет расстояние меток от оси. Применяется к оси категорий или дат. Значение должно быть от 0% до 1000%. Чтение/записьUInt16 . |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Представляет основание логарифма. Значение по умолчанию: 10. Чтение/запись.Double . |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Представляет основной формат линий сетки на оси диаграммы. Только для чтения[`IChartLinesFormat`](../ichartlinesformat) . |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Представляет тип основной отметки для указанной оси. Чтение/запись[`TickMarkType`](../tickmarktype) . |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Представляет основные единицы для оси дат или значений. Чтение/записьDouble . |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Представляет шкалу основных единиц для оси дат. Чтение/запись[`TimeUnitType`](../timeunittype) . |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Представляет максимальное значение на оси значений. Чтение/записьDouble . |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Представляет второстепенный формат линий сетки на оси диаграммы. Только для чтения[`IChartLinesFormat`](../ichartlinesformat) . |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Представляет тип второстепенной отметки для указанной оси. Чтение/запись[`TickMarkType`](../tickmarktype) . |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Представляет младшие единицы для оси даты или значения. Чтение/записьDouble . |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Представляет шкалу основных единиц для оси дат. Чтение/запись[`TimeUnitType`](../timeunittype) . |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Представляет минимальное значение на оси значений. Чтение/записьDouble . |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Представляет строку формата для меток оси. Чтение/записьString . |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Указывает количество бинов, когда для свойства AggregationType установлено значение AxisAggregationType.ByNumberOfBins. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Определяет пользовательское значение корзины переполнения. Применяется, когда свойство IsAutomaticOverflowBin имеет значение false, а свойство IsOverflowBin равно true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Представляет положение оси. Чтение/запись[`AxisPositionType`](../axispositiontype) . |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Чтобы скрыть основную линию сетки, задайте для MajorGridLinesFormat.Line.FillFormat.FillType значение FillType.NoFill. Только для чтенияBoolean . |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Чтобы скрыть второстепенные линии сетки, задайте для параметра MinorGridLinesFormat.Line.FillFormat.FillType значение FillType.NoFill. Только для чтенияBoolean . |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Представляет формат текста. Только для чтения[`IChartTextFormat`](../icharttextformat) . |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Представляет положение меток делений на указанной оси. Чтение/запись[`TickLabelPositionType`](../ticklabelpositiontype) . |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Представляет угол поворота меток деления. Чтение/записьSingle . |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Указывает, сколько делений следует пропускать между отображаемыми метками. Применяется к оси категорий или серий. Чтение/записьUInt32 . |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Определяет, сколько меток должно быть пропущено, прежде чем будет нарисована следующая . Применяется к оси категорий или серий. Чтение/записьUInt16 . |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Получает название оси. Только для чтения[`IChartTitle`](../icharttitle) . |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Указывает пользовательское значение корзины для недорасхода. Применяется, когда свойство IsAutomaticUnderflowBin имеет значение false, а свойство IsUnderflowBin равно true. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Задает для свойства IAxis.CategoryAxisType значение, которое определяется автоматически на основе данных оси. |

### Смотрите также

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [AxesManager](../axesmanager)
* interface [IAxis](../iaxis)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
