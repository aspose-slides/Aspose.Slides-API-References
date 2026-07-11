---
title: ChartDataWorkbook
second_title: Aspose.Slides για Android μέσω Java API
description: Παρέχει πρόσβαση σε ενσωματωμένο βιβλίο εργασίας Excel
type: docs
url: /el/com.aspose.slides/chartdataworkbook/
---
**Κληρονομικότητα:**
java.lang.Object, com.aspose.slides.DomObject

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Παρέχει πρόσβαση σε ενσωματωμένο βιβλίο εργασίας Excel
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Λαμβάνει μια συλλογή από φύλλα εργασίας. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Λαμβάνει το σύνολο των κελιών. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος |
| [clear(int sheetIndex)](#clear-int-) | Καθαρίζει όλες τις τιμές των κελιών στο φύλλο |
| [calculateFormulas()](#calculateFormulas--) | Υπολογίζει όλους τους τύπους στο βιβλίο εργασίας και ενημερώνει τις αντίστοιχες τιμές των κελιών. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


Λαμβάνει μια συλλογή από φύλλα εργασίας.

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

**Επιστρέφει:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Λαμβάνει το σύνολο των κελιών.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | java.lang.String | Τύπος Excel όπως "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Εάν είναι true, η μέθοδος επιστρέφει τη συλλογή χωρίς κρυμμένα κελιά. |

**Επιστρέφει:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetName | java.lang.String | Όνομα του φύλλου εργασίας. |
| row | int | Η σειρά. |
| column | int | Η στήλη. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| row | int | Η σειρά. |
| column | int | Η στήλη. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| cellName | java.lang.String | Όνομα του κελιού. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| cellName | java.lang.String | Όνομα του κελιού. |
| value | java.lang.Object | Η τιμή. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Λαμβάνει το κελί που μπορεί να χρησιμοποιηθεί για σειρές ή κατηγορίες διαγράμματος

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας. |
| row | int | Η σειρά. |
| column | int | Η στήλη. |
| value | java.lang.Object | Η τιμή. |

**Επιστρέφει:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


Καθαρίζει όλες τις τιμές των κελιών στο φύλλο

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sheetIndex | int | Δείκτης του φύλλου |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Υπολογίζει όλους τους τύπους στο βιβλίο εργασίας και ενημερώνει τις αντίστοιχες τιμές των κελιών.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```