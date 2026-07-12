---
title: IChartDataWorksheetCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa a coleção de planilhas da pasta de trabalho de dados do gráfico.
type: docs
url: /pt/com.aspose.slides/ichartdataworksheetcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Representa a coleção de planilhas da pasta de trabalho de dados do gráfico.

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

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna a planilha pelo índice. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Retorna a planilha pelo índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da planilha na coleção. |

**Retorna:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instância de IChartDataWorksheet.