---
title: IChartDataWorksheetCollection
second_title: Referencia de API de Java para Aspose.Slides para Android
description: Representa la colección de hojas de cálculo del libro de datos del gráfico.
type: docs
url: /es/com.aspose.slides/ichartdataworksheetcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Representa la colección de hojas de cálculo del libro de datos del gráfico.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la hoja de cálculo por índice. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Devuelve la hoja de cálculo por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la hoja de cálculo en la colección. |

**Devuelve:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instancia de IChartDataWorksheet.