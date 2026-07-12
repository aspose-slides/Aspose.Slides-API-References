---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides for Android ile Java API Referansı
description: Grafik veri çalışma kitabının çalışma sayfalarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdataworksheetcollection/
---
**Uygulanan Tüm Arabirimler:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Grafik veri çalışma kitabının çalışma sayfalarının koleksiyonunu temsil eder.

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
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndekse göre çalışma sayfasını döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

İndekse göre çalışma sayfasını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Koleksiyondaki çalışma sayfasının indeksi. |

**Döndürür:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet örneği.