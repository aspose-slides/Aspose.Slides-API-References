---
title: DataLabel
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет метки серии.
type: docs
weight: 1410
url: /ru/net/aspose.slides.charts/datalabel/
---
## DataLabel class

Представляет метки серии.

```csharp
public class DataLabel : IDataLabel
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [DataLabel](datalabel)(IChartDataPoint) | Создает новый экземпляр класса DataLabel. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ActualHeight](../../aspose.slides.charts/datalabel/actualheight) { get; } | Определяет фактическую высоту элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. ЧитатьSingle. |
| [ActualWidth](../../aspose.slides.charts/datalabel/actualwidth) { get; } | Задает фактическую ширину элемента диаграммы. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. ЧитатьSingle. |
| [ActualX](../../aspose.slides.charts/datalabel/actualx) { get; } | Задает фактическое положение x (слева) элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. ЧитатьSingle. |
| [ActualY](../../aspose.slides.charts/datalabel/actualy) { get; } | Указывает фактическую вершину элемента диаграммы относительно левого верхнего угла диаграммы. Вызовите метод IChart.ValidateChartLayout() перед тем, как получить фактические значения. ЧитатьSingle. |
| [Bottom](../../aspose.slides.charts/datalabel/bottom) { get; } | Снизу. Только для чтенияSingle. |
| [Chart](../../aspose.slides.charts/datalabel/chart) { get; } | Возвращает родительскую диаграмму. Только для чтения[`IChart`](../ichart). |
| [DataLabelFormat](../../aspose.slides.charts/datalabel/datalabelformat) { get; } | Возвращает формат метки данных. Только для чтения[`IDataLabelFormat`](../idatalabelformat). |
| [Height](../../aspose.slides.charts/datalabel/height) { get; set; } | Возвращает или задает высоту заголовка как часть высоты диаграммы. Чтение/записьSingle. |
| [IsVisible](../../aspose.slides.charts/datalabel/isvisible) { get; } | False означает, что метка данных не видна (поэтому все флаги Show* (ShowValue, ...) ложны). Только чтениеBoolean. |
| [Right](../../aspose.slides.charts/datalabel/right) { get; } | Верно. Только для чтенияSingle. |
| [TextFormat](../../aspose.slides.charts/datalabel/textformat) { get; } | Возвращает текстовый формат. Только чтение[`IChartTextFormat`](../icharttextformat). |
| [TextFrameForOverriding](../../aspose.slides.charts/datalabel/textframeforoverriding) { get; } | Может содержать форматированный текст. Если это свойство не равно null, то это форматированное текстовое значение переопределяет автоматически сгенерированный текст метки данных. Автоматически сгенерированный текст метки данных означает текст, управляемый свойствами ShowSeriesName, ShowValue, ... и отформатированный с помощью свойства TextFormatManager.TextFormat. Только для чтения[`ITextFrame`](../../aspose.slides/itextframe). |
| [ValueFromCell](../../aspose.slides.charts/datalabel/valuefromcell) { get; set; } | Получает или задает ячейку данных рабочей книги. Применяется, если свойство IDataLabelFormat.ShowLabelValueFromCell равно true. |
| [Width](../../aspose.slides.charts/datalabel/width) { get; set; } | Возвращает или задает ширину заголовка как часть ширины диаграммы. Чтение/записьSingle. |
| [X](../../aspose.slides.charts/datalabel/x) { get; set; } | Возвращает или задает координату x заголовка как часть ширины диаграммы. Чтение/записьSingle. |
| [Y](../../aspose.slides.charts/datalabel/y) { get; set; } | Возвращает или задает координату y заголовка как часть высоты диаграммы. Чтение/записьSingle. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddTextFrameForOverriding](../../aspose.slides.charts/datalabel/addtextframeforoverriding)(string) | Инициализировать TextFrameForOverriding с текстом в параметре "text". Если TextFrameForOverriding уже инициализирован, то просто меняет свой текст. |
| [GetActualLabelText](../../aspose.slides.charts/datalabel/getactuallabeltext)() | Возвращает фактический текст метки на основе настроек DataLabelFormat или значения TextFrameForOverriding.Text. |
| [Hide](../../aspose.slides.charts/datalabel/hide)() | Сделать метку данных скрытой, установив все флаги Show* (ShowValue, ...) в ложное состояние. IsVisible после этого будет false. |

### Смотрите также

* interface [IDataLabel](../idatalabel)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->