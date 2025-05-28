---
title: IChartDataCell
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una celda para datos de gráficos.
type: docs
weight: 1730
url: /es/aspose.slides.charts/ichartdatacell/
---

## Interfaz IChartDataCell

Representa una celda para datos de gráficos.

```csharp
public interface IChartDataCell
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ChartDataWorksheet](../../aspose.slides.charts/ichartdatacell/chartdataworksheet) { get; } | Obtiene la hoja de cálculo. Solo lectura [`IChartDataWorksheet`](../ichartdataworksheet). |
| [Column](../../aspose.slides.charts/ichartdatacell/column) { get; } | Devuelve el índice de la columna de la hoja de cálculo en la que se encuentra la celda. Solo lectura Int32. |
| [CustomNumberFormat](../../aspose.slides.charts/ichartdatacell/customnumberformat) { get; set; } | Obtiene o establece el formato de visualización personalizado de números y fechas. Si el valor está vacío, se usará el valor PresetNumberFormat. Lectura/escritura String. |
| [Formula](../../aspose.slides.charts/ichartdatacell/formula) { get; set; } | Obtiene o establece la fórmula en estilo A1. |
| [IsHidden](../../aspose.slides.charts/ichartdatacell/ishidden) { get; } | Determina si la celda está oculta. Solo lectura Boolean. |
| [PresetNumberFormat](../../aspose.slides.charts/ichartdatacell/presetnumberformat) { get; set; } | Obtiene o establece el formato de visualización incorporado de números y fechas. El número preestablecido debe estar en [0..22] o [37..49]. Lectura/escritura Byte. |
| [R1C1Formula](../../aspose.slides.charts/ichartdatacell/r1c1formula) { get; set; } | Obtiene o establece la fórmula en estilo R1C1. |
| [Row](../../aspose.slides.charts/ichartdatacell/row) { get; } | Devuelve el índice de la fila de la hoja de cálculo en la que se encuentra la celda. Solo lectura Int32. |
| [Value](../../aspose.slides.charts/ichartdatacell/value) { get; set; } | Obtiene o establece el valor de una celda. Lectura/escritura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Calculate](../../aspose.slides.charts/ichartdatacell/calculate)(bool) | Si la celda contiene una fórmula, el valor se actualizará en función de esa fórmula. |

### También Visto

* espacio de nombres [Aspose.Slides.Charts](../../aspose.slides.charts)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->