---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides για Android μέσω αναφοράς Java API
description: Αναπαριστά τη συλλογή των φύλλων εργασίας του βιβλίου δεδομένων γραφήματος.
type: docs
url: /el/com.aspose.slides/ichartdataworksheetcollection/
---
**Όλες οι Υλοποιημένες Διεπαφές:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Αναπαριστά τη συλλογή των φύλλων εργασίας του φύλλου δεδομένων γραφήματος.

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
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Επιστρέφει το φύλλο εργασίας βάσει δείκτη. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


Επιστρέφει το φύλλο εργασίας βάσει δείκτη.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Δείκτης του φύλλου εργασίας στη συλλογή. |

**Επιστρέφει:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Παράδειγμα του IChartDataWorksheet.