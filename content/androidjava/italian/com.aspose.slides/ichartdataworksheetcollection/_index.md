---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta la raccolta di fogli di lavoro della cartella dati del grafico.
type: docs
url: /it/com.aspose.slides/ichartdataworksheetcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Rappresenta la raccolta di fogli di lavoro della cartella dati del grafico.

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
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce il foglio di lavoro per indice. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


Restituisce il foglio di lavoro per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del foglio di lavoro nella raccolta. |

**Restituisce:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Istanza di IChartDataWorksheet.