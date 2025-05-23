---
title: IDataLabelFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет параметры форматирования для DataLabel.
type: docs
weight: 1900
url: /ru/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat interface

Представляет параметры форматирования для DataLabel.

```csharp
public interface IDataLabelFormat : IFormattedTextContainer
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/idatalabelformat/asiformattedtextcontainer) { get; } | Позволяет получить базовый интерфейс IFormattedTextContainer. Только для чтения[`IFormattedTextContainer`](../iformattedtextcontainer). |
| [Format](../../aspose.slides.charts/idatalabelformat/format) { get; } | Представляет формат метки данных. Только для чтения[`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/idatalabelformat/isnumberformatlinkedtosource) { get; set; } | Чтение/записьBoolean. |
| [NumberFormat](../../aspose.slides.charts/idatalabelformat/numberformat) { get; set; } | Представляет строку формата для объекта DataLabels. Чтение/записьString. |
| [Position](../../aspose.slides.charts/idatalabelformat/position) { get; set; } | Представляет позицию метки данных. Чтение/запись[`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/idatalabelformat/separator) { get; set; } | Задает или возвращает Variant, представляющий разделитель, используемый для меток данных на диаграмме. Чтение/записьString. |
| [ShowBubbleSize](../../aspose.slides.charts/idatalabelformat/showbubblesize) { get; set; } | Представляет поведение отображения значения размера пузырька метки данных указанной диаграммы. True отображает значение размера пузырька. Ложь скрывать. Чтение/записьBoolean. |
| [ShowCategoryName](../../aspose.slides.charts/idatalabelformat/showcategoryname) { get; set; } | Представляет поведение отображения имени категории метки данных указанной диаграммы. Значение true, чтобы отобразить имя категории для меток данных на диаграмме. Ложь скрывать. Чтение/записьBoolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/idatalabelformat/showlabelasdatacallout) { get; set; } | Определяет, будет ли указанная метка данных диаграммы отображаться как выноска данных или как метка данных.  Если родителем этого объекта DataLabelFormat является коллекция меток данных DataLabelCollection, то это свойство получает или задает значение по умолчанию значение свойства ShowLabelAsDataCallout для новых меток данных в коллекции DataLabelCollection. Присвоение этому свойству значения также устанавливает это значение в свойство ShowLabelAsDataCallout для всех меток данных в коллекции DataLabelCollection (т.е. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" приводит к тому, что все DataLabels[i].ShowLabelAsDataCallout равно val). |
| [ShowLabelValueFromCell](../../aspose.slides.charts/idatalabelformat/showlabelvaluefromcell) { get; set; } | Представляет поведение отображения значения ячейки метки данных указанной диаграммы. True отображает значение ячейки. Ложь скрывать. Чтение/записьBoolean. |
| [ShowLeaderLines](../../aspose.slides.charts/idatalabelformat/showleaderlines) { get; set; } | Представляет поведение отображения линий выноски меток данных указанной диаграммы. True отображает линии выноски. Ложь скрывать. Чтение/записьBoolean. |
| [ShowLegendKey](../../aspose.slides.charts/idatalabelformat/showlegendkey) { get; set; } | Представляет поведение отображения клавиши легенды метки данных указанной диаграммы. True, если ключ легенды метки данных виден. Чтение/записьBoolean. |
| [ShowPercentage](../../aspose.slides.charts/idatalabelformat/showpercentage) { get; set; } | Представляет поведение отображения процентного значения метки данных указанной диаграммы. True отображает процентное значение. Ложь скрывать. Чтение/записьBoolean. |
| [ShowSeriesName](../../aspose.slides.charts/idatalabelformat/showseriesname) { get; set; } | Возвращает или задает логическое значение, указывающее поведение отображения имени ряда для меток данных на диаграмме. True, чтобы показать название серии. Ложь скрывать. Чтение/записьBoolean. |
| [ShowValue](../../aspose.slides.charts/idatalabelformat/showvalue) { get; set; } | Представляет поведение отображения процентного значения метки данных указанной диаграммы. True отображает процентное значение. Ложь скрывать. Чтение/записьBoolean. |

### Смотрите также

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
