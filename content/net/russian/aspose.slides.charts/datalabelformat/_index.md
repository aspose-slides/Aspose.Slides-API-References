---
title: DataLabelFormat
second_title: Справка по API Aspose.Sildes для .NET
description: Представляет параметры форматирования для DataLabel.
type: docs
weight: 1490
url: /ru/aspose.slides.charts/datalabelformat/
---

## Класс DataLabelFormat

Представляет параметры форматирования для DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Возвращает диаграмму. Только для чтения [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Представляет формат метки данных. Только для чтения [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Булево значение для чтения/записи. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Представляет строку формата для объекта DataLabels. Строка для чтения/записи. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Представляет позицию метки данных. Значение для чтения/записи [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Устанавливает или возвращаетVariant, представляющий разделитель, используемый для меток данных на диаграмме. Строка для чтения/записи. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Представляет поведение отображения значения размера пузырька метки данных диаграммы. True отображает значение размера пузырька. False скрывает. Булево значение для чтения/записи. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Представляет поведение отображения имени категории метки данных диаграммы. True для отображения имени категории для меток данных на диаграмме. False для скрытия. Булево значение для чтения/записи. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Определяет, будет ли указанная метка данных диаграммы отображаться как вызов данных или как метка данных. Если родителем этого объекта DataLabelFormat является коллекция DataLabelCollection, то это свойство получает или устанавливает значение по умолчанию для свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Установка этого свойства с значением также устанавливает это значение для свойства ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" приведет к тому, что все DataLabels[i].ShowLabelAsDataCallout будут равны val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Представляет поведение отображения значения ячейки метки данных диаграммы. True отображает значение ячейки. False скрывает. Булево значение для чтения/записи. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Представляет поведение отображения линий лидеров метки данных диаграммы. True отображает линии лидеров. False скрывает. Булево значение для чтения/записи. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Представляет поведение отображения ключа легенды метки данных диаграммы. True, если ключ легенды метки данных виден. Булево значение для чтения/записи. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Представляет поведение отображения значения процента метки данных диаграммы. True отображает значение процента. False скрывает. Булево значение для чтения/записи. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Возвращает или устанавливает булево значение, указывающее поведение отображения имени серии для меток данных на диаграмме. True для отображения имени серии. False для скрытия. Булево значение для чтения/записи. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Представляет поведение отображения значения метки данных диаграммы. True отображает значение. False скрывает. Булево значение для чтения/записи. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Возвращает формат текста диаграммы. Только для чтения [`IChartTextFormat`](../icharttextformat). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает код хеша. |

### См. Также

* класс [PVIObject](../../aspose.slides/pviobject)
* интерфейс [IDataLabelFormat](../idatalabelformat)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->