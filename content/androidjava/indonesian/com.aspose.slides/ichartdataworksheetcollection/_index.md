---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides untuk Android lewat Referensi API Java
description: Mewakili koleksi lembar kerja dari buku kerja data bagan.
type: docs
url: /id/com.aspose.slides/ichartdataworksheetcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Mewakili koleksi lembar kerja dari buku kerja data diagram.

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
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan lembar kerja berdasarkan indeks. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Mengembalikan lembar kerja berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks lembar kerja dalam koleksi. |

**Mengembalikan:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instansi dari IChartDataWorksheet.