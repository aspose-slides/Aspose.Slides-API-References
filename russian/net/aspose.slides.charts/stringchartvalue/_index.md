---
title: StringChartValue
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет строковое значение которое может быть сохранено в документе презентации pptx двумя способами 1 в ячейке/ячейках рабочей книги связанной с диаграммой 2 как буквальное значение.
type: docs
weight: 2270
url: /ru/net/aspose.slides.charts/stringchartvalue/
---
## StringChartValue class

Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами: 1) в ячейке/ячейках рабочей книги, связанной с диаграммой; 2) как буквальное значение.

```csharp
public class StringChartValue : BaseChartValue, IStringChartValue
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsCells](../../aspose.slides.charts/stringchartvalue/ascells) { get; set; } | Назначение нулевого значения не разрешено. Возвращаемое значение всегда не является нулевым. Чтение/запись[`IChartCellCollection`](../ichartcellcollection) . |
| [AsLiteralString](../../aspose.slides.charts/stringchartvalue/asliteralstring) { get; set; } | Возвращает или задает значение как литеральную строку. Чтение/записьString . |
| override [Data](../../aspose.slides.charts/stringchartvalue/data) { get; set; } | Возвращает или устанавливает объект данных. Чтение/записьObject . |
| [DataSourceType](../../aspose.slides.charts/basechartvalue/datasourcetype) { get; set; } | Указывает, является ли свойство AsCell, AsCells, AsLiteralString или AsLiteralDouble действительным в потомках. Другими словами, он указывает тип значения свойства Data. Чтение/запись[`DataSourceType`](../datasourcetype) . |

## Методы

| Имя | Описание |
| --- | --- |
| [GetCellsAddressInWorkbook](../../aspose.slides.charts/stringchartvalue/getcellsaddressinworkbook)() | Если свойство DataSourceType имеет значение DataSourceType.Worksheet, то этот метод возвращает адрес ячеек в книге, которые представляют строковые данные. В противном случае return пустая строка. |
| [SetFromOneCell](../../aspose.slides.charts/stringchartvalue/setfromonecell)(IChartDataCell) | Устанавливает значение из указанной ячейки. |
| override [ToString](../../aspose.slides.charts/stringchartvalue/tostring)() | Возвращает данные строкового значения. Возвращает значение null, если DataSourceType имеет значение false и строковое значение не было назначено. |

### Смотрите также

* class [BaseChartValue](../basechartvalue)
* interface [IStringChartValue](../istringchartvalue)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
