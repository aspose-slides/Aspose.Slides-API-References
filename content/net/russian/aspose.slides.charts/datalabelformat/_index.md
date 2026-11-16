---
title: DataLabelFormat
second_title: Aspose.Sildes для .NET справочник API
description: Представляет параметры форматирования для DataLabel.
type: docs
weight: 1580
url: /ru/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat класс

Представляет параметры форматирования для DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | Возвращает диаграмму. Только для чтения [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | Представляет формат метки данных. Только для чтения [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | Чтение/запись Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | Представляет строку формата для объекта DataLabels. Чтение/запись String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | Представляет положение метки данных. Чтение/запись [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | Устанавливает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме. Чтение/запись String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | Представляет поведение отображения значения размера пузыря метки данных указанной диаграммы. True отображает значение размера пузыря. False скрывает. Чтение/запись Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | Представляет поведение отображения имени категории метки данных указанной диаграммы. True отображает имя категории для меток данных на диаграмме. False скрывает. Чтение/запись Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | Определяет, будет ли метка данных указанной диаграммы отображаться как выноска данных или как метка данных. Если родителем данного объекта DataLabelFormat является коллекция DataLabelCollection меток данных, то это свойство получает или задает значение по умолчанию свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Установка этого свойства также задает значение свойства ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (например, "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" приводит к тому, что у всех DataLabels[i].ShowLabelAsDataCallout будет значение val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | Представляет поведение отображения значения ячейки метки данных указанной диаграммы. True отображает значение ячейки. False скрывает. Чтение/запись Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | Представляет поведение отображения линий-выноски метки данных указанной диаграммы. True отображает линии-выноски. False скрывает. Чтение/запись Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | Представляет поведение отображения ключа легенды метки данных указанной диаграммы. True, если ключ легенды метки данных виден. Чтение/запись Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | Представляет поведение отображения процентного значения метки данных указанной диаграммы. True отображает процентное значение. False скрывает. Чтение/запись Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | Возвращает или задаёт Boolean, указывающий поведение отображения имени серии для меток данных на диаграмме. True отображает имя серии. False скрывает. Чтение/запись Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | Представляет поведение отображения процентного значения метки данных указанной диаграммы. True отображает процентное значение. False скрывает. Чтение/запись Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | Возвращает формат текста диаграммы. Только для чтения [`IChartTextFormat`](../icharttextformat). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### Смотрите также

* класс [PVIObject](../../aspose.slides/pviobject)
* интерфейс [IDataLabelFormat](../idatalabelformat)
* пространство имён [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->