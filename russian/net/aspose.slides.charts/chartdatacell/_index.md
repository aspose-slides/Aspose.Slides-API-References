---
title: ChartDataCell
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет ячейку для данных диаграммы.
type: docs
weight: 1180
url: /ru/net/aspose.slides.charts/chartdatacell/
---
## ChartDataCell class

Представляет ячейку для данных диаграммы.

```csharp
public class ChartDataCell : IChartDataCell
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ChartDataWorksheet](../../aspose.slides.charts/chartdatacell/chartdataworksheet) { get; } | Получает рабочий лист. Только для чтения[`IChartDataWorksheet`](../ichartdataworksheet). |
| [Column](../../aspose.slides.charts/chartdatacell/column) { get; } | Возвращает индекс столбца рабочего листа, в котором находится ячейка. Только для чтенияInt32. |
| [CustomNumberFormat](../../aspose.slides.charts/chartdatacell/customnumberformat) { get; set; } | Получает или задает настраиваемый формат отображения чисел и дат. Если значение пустое, будет использоваться значение PresetNumberFormat. Чтение/записьString. |
| [Formula](../../aspose.slides.charts/chartdatacell/formula) { get; set; } | Получает или задает формулу в стиле A1. |
| [IsHidden](../../aspose.slides.charts/chartdatacell/ishidden) { get; } | Определяет, скрыта ли ячейка. Только чтениеBoolean. |
| [PresetNumberFormat](../../aspose.slides.charts/chartdatacell/presetnumberformat) { get; set; } | Получает или задает встроенный формат отображения чисел и дат. Номер предустановки должен быть в диапазоне [0..22] или [37..49]". Чтение/записьByte. |
| [R1C1Formula](../../aspose.slides.charts/chartdatacell/r1c1formula) { get; set; } | Получает или задает формулу в стиле R1C1. |
| [Row](../../aspose.slides.charts/chartdatacell/row) { get; } | Возвращает индекс строки рабочего листа, в которой находится ячейка. Только для чтенияInt32. |
| [Value](../../aspose.slides.charts/chartdatacell/value) { get; set; } | Получает или задает значение. Чтение/записьObject. |

## Методы

| Имя | Описание |
| --- | --- |
| [Calculate](../../aspose.slides.charts/chartdatacell/calculate)(bool) | Если ячейка содержит формулу, значение будет обновлено на основе этой формулы. |

### Смотрите также

* interface [IChartDataCell](../ichartdatacell)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->