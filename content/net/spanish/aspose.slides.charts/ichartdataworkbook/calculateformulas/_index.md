---
title: CalculateFormulas
second_title: Referencia de API de Aspose.Slides para .NET
description: Calcula todas las fórmulas en el libro de trabajo y actualiza los valores de las celdas correspondientes.
type: docs
weight: 20
url: /es/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---

## Método IChartDataWorkbook.CalculateFormulas

Calcula todas las fórmulas en el libro de trabajo y actualiza los valores de las celdas correspondientes.

```csharp
public void CalculateFormulas()
```

### Excepciones

| excepción | condición |
| --- | --- |
| [CellCircularReferenceException](../../../aspose.slides.spreadsheet/cellcircularreferenceexception) | El libro de trabajo contiene fórmulas con una referencia circular. |
| [CellUnsupportedDataException](../../../aspose.slides.spreadsheet/cellunsupporteddataexception) | Los datos de la celda no son compatibles. |

### Ejemplos

El ejemplo muestra cómo asignar una fórmula a la celda y calcular un valor. El valor de la celda "B4" se establece en 5.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IChart chart = pres.Slides[0].Shapes.AddChart(ChartType.Pie, 100, 100, 300, 400);
    IChartDataWorkbook wb = chart.ChartData.ChartDataWorkbook;
    wb.GetCell(0, "B2", 2);	
	wb.GetCell(0, "B3", 3);	
    wb.GetCell(0, "B4").Formula = "B2+B3";
    wb.CalculateFormulas();
    ...
}
```

### Véase también

* interfaz [IChartDataWorkbook](../../ichartdataworkbook)
* namespace [Aspose.Slides.Charts](../../ichartdataworkbook)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->