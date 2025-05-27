---
title: Ось
second_title: Справочник по API Aspose.Slides для .NET
description: Инкапсулирует объект, который представляет ось графика.
type: docs
weight: 1100
url: /ru/aspose.slides.charts/axis/
---

## Класс Axis

Инкапсулирует объект, который представляет ось графика.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## Свойства

| Название | Описание |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | Указывает фактическую основную единицу оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | Указывает фактическую шкалу основной единицы оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | Указывает фактическое максимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | Указывает фактическую меньшую единицу оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | Указывает фактическую шкалу меньшей единицы оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | Указывает фактическое минимальное значение на оси. Сначала вызовите метод IChart.ValidateChartLayout(), чтобы получить фактическое значение. |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | Представляет тип агрегации категории оси (группировка). Применяется к категориям. Используется только с сериями Гистограмма или ГистограммаПарето. |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | Представляет, пересекает ли ось значений ось категорий между категориями. Это свойство применяется только к категориальным осям и не применяется к 3-D графикам. Читаемое/Записываемое логическое значение. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | Указывает наименьшую единицу времени, которая представлена на оси дат. Читаемое/Записываемое [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | Указывает ширину группы, когда значение свойства AggregationType установлено на AxisAggregationType.ByBinWidth. Применяется к категориальным осям. Используется только с сериями Гистограмма или ГистограммаПарето. |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | Указывает тип категориальной оси. Читаемое/Записываемое [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | Возвращает родительский график. Только для чтения [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | Представляет точку на оси, где перпендикулярная ось ее пересекает. Читаемое/Записываемое значение типа Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | Представляет CrossType на указанной оси, где пересекается другая ось. Читаемое/Записываемое [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | Указывает значение масштабирования единиц отображения для оси значений. Читаемое/Записываемое [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | Представляет формат оси. Только для чтения [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | Определяет, имеет ли ось видимый заголовок. Читаемое/Записываемое логическое значение. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | Указывает, назначена ли основная единица оси автоматически. Читаемое/Записываемое логическое значение. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | Указывает, назначено ли максимальное значение автоматически. Читаемое/Записываемое логическое значение. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | Указывает, назначена ли меньшая единица оси автоматически. Читаемое/Записываемое логическое значение. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | Указывает, назначено ли минимальное значение автоматически. Читаемое/Записываемое логическое значение. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | Указывает автоматическое значение переполнения группы. Если false: используйте свойство OverflowBin. |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | Указывает автоматическое значение расстояния между метками делений. Если false: используйте свойство TickLabelSpacing. Читаемое/Записываемое логическое значение. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | Указывает автоматическое значение расстояния между делениями. Если false: используйте свойство TickMarksSpacing. Читаемое/Записываемое логическое значение. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | Указывает автоматическое значение недополненной группы. Если false: используйте свойство UnderflowBin. |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | Представляет, является ли масштаб оси значений логарифмическим. Читаемое/Записываемое логическое значение. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | Указывает, связано ли форматирование с источником данных. Читаемое/Записываемое логическое значение. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | Указывает, применяется ли группа переполнения. Используйте IsAutomaticOverflowBin и OverflowBin для настройки значения переполнения. |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | Представляет, создает ли MS PowerPoint график, начиная с последних данных. Читаемое/Записываемое логическое значение. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | Указывает, применяется ли группа недополнения. Используйте IsAutomaticUnderflowBin и UnderflowBin для настройки значения недополнения. |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | Представляет, видима ли ось. Читаемое/Записываемое логическое значение. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | Указывает расстояние меток от оси. Применяется к категориальным или датированным осям. Значение должно быть между 0% и 1000%. Читаемое/Записываемое UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | Представляет логарифмическую базу. Значение по умолчанию – 10. Читаемое/Записываемое Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | Представляет формат основных сеток на оси графика. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | Представляет тип основной метки деления для указанной оси. Читаемое/Записываемое [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | Представляет основные единицы для оси дат или значений. Читаемое/Записываемое Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | Представляет шкалу основной единицы для оси дат. Читаемое/Записываемое [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | Представляет максимальное значение на оси значений. Читаемое/Записываемое Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | Представляет формат меньших сеток на оси графика. Только для чтения [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | Представляет тип меньшей метки деления для указанной оси. Читаемое/Записываемое [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | Представляет меньшие единицы для оси дат или значений. Читаемое/Записываемое Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | Представляет шкалу основной единицы для оси дат. Читаемое/Записываемое [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | Представляет минимальное значение на оси значений. Читаемое/Записываемое Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Представляет строку формата для меток оси. Читаемое/Записываемое String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | Указывает количество групп, когда значение свойства AggregationType установлено на AxisAggregationType.ByNumberOfBins. Применяется к категориальным осям. Используется только с сериями Гистограмма или ГистограммаПарето. |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | Указывает настраиваемое значение группы переполнения. Применяется, когда свойство IsAutomaticOverflowBin установлено в false, а свойство IsOverflowBin равно true. |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | Представляет позицию оси. Читаемое/Записываемое [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | Чтобы скрыть основные линии сетки, установите MajorGridLinesFormat.Line.FillFormat.FillType в FillType.NoFill. Только для чтения логическое значение. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | Чтобы скрыть меньшие линии сетки, установите MinorGridLinesFormat.Line.FillFormat.FillType в FillType.NoFill. Только для чтения логическое значение. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | Представляет формат текста. Только для чтения [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | Представляет позицию меток на указанной оси. Читаемое/Записываемое [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | Представляет угол поворота меток делений. Читаемое/Записываемое значение типа Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | Указывает, сколько меток делений пропустить между метками, которые будут нарисованы. Применяется к категориальным или серийным осям. Читаемое/Записываемое UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | Указывает, сколько меток делений следует пропустить перед тем, как нарисовать следующую. Применяется к категориальным или серийным осям. Читаемое/Записываемое UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | Получает заголовок оси. Только для чтения [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | Указывает настраиваемое значение группы недополнения. Применяется, когда свойство IsAutomaticUnderflowBin установлено в false, а свойство IsUnderflowBin равно true. |

## Методы

| Название | Описание |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | Устанавливает свойство IAxis.CategoryAxisType со значением, которое автоматически определяется на основе данных оси. |

### См. также

* класс [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* класс [AxesManager](../axesmanager)
* интерфейс [IAxis](../iaxis)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->