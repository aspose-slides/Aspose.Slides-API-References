---
title: IAxis
second_title: Справочник по API Aspose.Slides для .NET
description: Инкапсулирует объект представляющий ось диаграммы.
type: docs
weight: 1570
url: /ru/net/aspose.slides.charts/iaxis/
---
## IAxis interface

Инкапсулирует объект, представляющий ось диаграммы.

```csharp
public interface IAxis : IFormattedTextContainer
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | Определяет фактическую основную единицу оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | Задает фактический масштаб основных единиц оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | Определяет фактическое максимальное значение на оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | Определяет фактическую вспомогательную единицу оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | Определяет фактический второстепенный масштаб оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | Определяет фактическое минимальное значение на оси. Вызовите метод IChart.ValidateChartLayout() ранее, чтобы получить фактическое значение. |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | Представляет тип агрегации оси категорий (биннинг). Применяется к категории. Используется только с сериями Histogram или HistogramPareto. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только для чтения[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | Указывает, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к осям категорий и не применяется к трехмерным диаграммам. Чтение/записьBoolean . |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | Указывает наименьшую единицу времени, представленную на оси даты. Чтение/запись[`TimeUnitType`](../timeunittype) . |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | Указывает ширину ячейки, когда для свойства AggregationType задано значение AxisAggregationType.ByBinWidth. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | Определяет тип оси категорий. Чтение/запись[`CategoryAxisType`](./categoryaxistype) . |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | Представляет точку на оси, где ее пересекает перпендикулярная ось. Чтение/записьSingle . |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | Представляет CrossType на указанной оси, где пересекается другая ось. Чтение/запись[`CrossesType`](../crossestype) . |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | Определяет значение масштабирования отображаемых единиц для оси значений. Чтение/запись[`DisplayUnitType`](../displayunittype) . |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | Представляет формат оси. Только для чтения[`IAxisFormat`](../iaxisformat) . |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | Определяет, имеет ли ось видимый заголовок. Чтение/записьBoolean . |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | Указывает, назначается ли автоматически основная единица оси. Чтение/записьBoolean . |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | Указывает, присваивается ли максимальное значение автоматически. Чтение/записьBoolean . |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | Указывает, назначается ли автоматически младшая единица оси. Чтение/записьBoolean . |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | Указывает, назначается ли минимальное значение автоматически. Чтение/записьBoolean . |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | Определяет значение корзины автоматического переполнения. Если false: использовать свойство OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | Задает значение автоматического интервала между метками деления. Если false: используйте свойство TickLabelSpacing. Чтение/записьBoolean . |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | Определяет значение интервала автоматических делений. Если false: используйте свойство TickMarksSpacing. Чтение/записьBoolean . |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | Определяет значение корзины для автоматического недополнения. Если false: использовать свойство UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | Указывает, является ли тип шкалы оси значений логарифмическим или нет. Чтение/записьBoolean . |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | Указывает, является ли формат связанными исходными данными. Чтение/записьBoolean . |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | Указывает, применяется ли бункер переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения корзины переполнения. |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | Указывает, отображает ли MS PowerPoint точки данных от последней к первой. Чтение/записьBoolean . |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | Указывает, применяется ли бункер нижнего переполнения. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения корзины для недорасхода. |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | Указывает, видна ли ось. Чтение/записьBoolean . |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | Определяет расстояние меток от оси. Применяется к оси категорий или дат. Значение должно быть от 0% до 1000%. Чтение/записьUInt16 . |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | Представляет основание логарифма. Значение по умолчанию: 10. Чтение/запись.Double . |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | Представляет основной формат линий сетки на оси диаграммы. Только для чтения[`IChartLinesFormat`](../ichartlinesformat) . |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | Представляет тип основной отметки для указанной оси. Чтение/запись[`TickMarkType`](../tickmarktype) . |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | Представляет основные единицы для оси дат или значений. Чтение/записьDouble . |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | Представляет шкалу основных единиц для оси дат. Чтение/запись[`TimeUnitType`](../timeunittype) . |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | Представляет максимальное значение на оси значений. Чтение/записьDouble . |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | Представляет второстепенный формат линий сетки на оси диаграммы. Только для чтения[`IChartLinesFormat`](../ichartlinesformat) . |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | Представляет тип второстепенной отметки для указанной оси. Чтение/запись[`TickMarkType`](../tickmarktype) . |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | Представляет младшие единицы для оси даты или значения. Чтение/записьDouble . |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | Представляет шкалу основных единиц для оси дат. Чтение/запись[`TimeUnitType`](../timeunittype) . |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | Представляет минимальное значение на оси значений. Чтение/записьDouble . |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | Представляет строку формата для меток оси. Чтение/записьString . |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | Указывает количество бинов, когда для свойства AggregationType установлено значение AxisAggregationType.ByNumberOfBins. Применяется к осям категорий. Используется только с сериями Histogram или HistogramPareto. |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | Определяет пользовательское значение корзины переполнения. Применяется, когда свойство IsAutomaticOverflowBin имеет значение false, а свойство IsOverflowBin равно true. |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | Представляет положение оси. Чтение/запись[`AxisPositionType`](../axispositiontype) . |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | Указывает, показаны ли основные линии сетки. Только для чтенияBoolean . |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | Указывает, показаны ли второстепенные линии сетки. Только для чтенияBoolean . |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | Представляет положение меток делений на указанной оси. Чтение/запись[`TickLabelPositionType`](../ticklabelpositiontype) . |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | Представляет угол поворота тиковых меток Чтение/записьSingle . |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | Определяет, сколько меток с делениями следует пропускать между отображаемыми метками. Чтение/записьUInt32 . |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | Определяет, сколько меток должно быть пропущено, прежде чем будет нарисована следующая . Применяется к оси категорий или серий. Чтение/записьUInt16 . |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | Получает название оси. Только для чтения[`IChartTitle`](../icharttitle) . |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | Указывает пользовательское значение корзины для недорасхода. Применяется, когда свойство IsAutomaticUnderflowBin имеет значение false, а свойство IsUnderflowBin равно true. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | Задает для свойства IAxis.CategoryAxisType значение, которое определяется автоматически на основе данных оси. |

### Смотрите также

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
