---
title: StringChartValue
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет строковое значение которое может быть сохранено в документе презентации pptx двумя способами 1 в ячейке/ячейках рабочей книги связанной с диаграммой 2 как буквальное значение.
type: docs
weight: 2270
url: /ru/aspose.slides.charts/stringchartvalue/
---
## StringChartValue class

Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.

```csharp
public class StringChartValue : BaseChartValue, IStringChartValue
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsCells](../../aspose.slides.charts/stringchartvalue/ascells) { get; set; } | Присвоение нулевого значения не допускается. Возвращаемое значение всегда не равно нулю. Чтение/запись[`IChartCellCollection`](../ichartcellcollection). |
| [AsLiteralString](../../aspose.slides.charts/stringchartvalue/asliteralstring) { get; set; } | Возвращает или устанавливает значение как литеральную строку. Чтение/записьString. |
| override [Data](../../aspose.slides.charts/stringchartvalue/data) { get; set; } | Возвращает или устанавливает объект данных. Чтение/записьObject. |
| [DataSourceType](../../aspose.slides.charts/basechartvalue/datasourcetype) { get; set; } | Указывает, является ли свойство AsCell, AsCells, AsLiteralString или AsLiteralDouble актуальным в потомках. Другими словами, он указывает тип значения свойства Data. Чтение/запись[`DataSourceType`](../datasourcetype). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetCellsAddressInWorkbook](../../aspose.slides.charts/stringchartvalue/getcellsaddressinworkbook)() | Если свойство DataSourceType имеет значение DataSourceType.Worksheet, то этот метод возвращает адрес ячеек в рабочей книге, которые представляют строковые данные. В противном случае вернуть пустую строку. |
| [SetFromOneCell](../../aspose.slides.charts/stringchartvalue/setfromonecell)(IChartDataCell) | Устанавливает значение из указанной ячейки. |
| override [ToString](../../aspose.slides.charts/stringchartvalue/tostring)() | Возвращает данные строкового значения. Возвращает null, если DataSourceType имеет значение false и строковое значение не было присвоено. |

### Смотрите также

* class [BaseChartValue](../basechartvalue)
* interface [IStringChartValue](../istringchartvalue)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
