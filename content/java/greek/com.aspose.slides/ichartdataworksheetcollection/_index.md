---
title: IChartDataWorksheetCollection
second_title: Αναφορά API Aspose.Slides για Java
description: Αντιπροσωπεύει τη συλλογή των φύλλων εργασίας του βιβλίου δεδομένων διαγράμματος.
type: docs
url: /el/com.aspose.slides/ichartdataworksheetcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Αντιπροσωπεύει τη συλλογή των φύλλων εργασίας του βιβλίου δεδομένων διαγράμματος.

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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το φύλλο εργασίας ανά δείκτη. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Επιστρέφει το φύλλο εργασίας ανά δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του φύλλου εργασίας στη συλλογή. |

**Επιστρέφει:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Παράδειγμα του IChartDataWorksheet.