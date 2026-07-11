---
title: IExcelDataWorkbook
second_title: Aspose.Slides για Android μέσω Java API Αναφορά
description: Αντιπροσωπεύει ένα βιβλίο εργασίας που παρέχει πρόσβαση σε δεδομένα Excel για γενική χρήση.
type: docs
url: /el/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Αντιπροσωπεύει ένα βιβλίο εργασίας που παρέχει πρόσβαση σε δεδομένα Excel για γενική χρήση.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Ανακτά μια συλλογή κελιών από το βιβλίο εργασίας που ταιριάζουν με τον καθορισμένο τύπο. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και τις συντεταγμένες του κελιού. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομα του και τις συντεταγμένες του κελιού. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και το όνομα κελιού σε μορφή Excel (π.χ., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομα κελιού σε μορφή Excel (π.χ., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Ανακτά ένα λεξικό που περιέχει τα ευρετικά και τα ονόματα όλων των διαγραμμάτων στο καθορισμένο φύλλο εργασίας ενός βιβλίου εργασίας Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Ανακτά τα ονόματα όλων των φύλλων εργασίας που περιέχονται στο βιβλίο εργασίας Excel. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Ανακτά μια συλλογή κελιών από το βιβλία εργασίας που ταιριάζουν με τον καθορισμένο τύπο.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Αποτέλεσμα: 5
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | java.lang.String | Μια φόρμουλα ή έκφραση περιοχής (π.χ., "Sheet1!A1:B3") που χρησιμοποιείται για τον προσδιορισμό των κελιών-στόχων. |
| skipHiddenCells | boolean | Εάν είναι true, τα κρυφά κελιά (π.χ., σε κρυφές γραμμές ή στήλες) θα εξαλειφθούν από το αποτέλεσμα. |

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Μια λίστα μόνο για ανάγνωση κελιών που ταιριάζουν με την καθορισμένη φόρμουλα.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και τις συντεταγμένες του κελιού.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας με βάση το μηδέν. |
| row | int | Δείκτης γραμμής του κελιού με βάση το μηδέν. |
| column | int | Δείκτης στήλης του κελιού με βάση το μηδέν. |

**Επιστρέφει:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Το κελί στην καθορισμένη θέση.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομα του και τις συντεταγμένες του κελιού.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας. |
| row | int | Δείκτης γραμμής του κελιού με βάση το μηδέν. |
| column | int | Δείκτης στήλης του κελιού με βάση το μηδέν. |

**Επιστρέφει:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Το κελί στην καθορισμένη θέση.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το δείκτη του και το όνομα κελιού σε μορφή Excel (π.χ., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetIndex | int | Δείκτης του φύλλου εργασίας με βάση το μηδέν. |
| cellName | java.lang.String | Η αναφορά κελιού σε μορφή Excel (π.χ., "A1", "C5"). |

**Επιστρέφει:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Το κελί στην καθορισμένη θέση.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


Ανακτά ένα κελί από το καθορισμένο φύλλο εργασίας χρησιμοποιώντας το όνομα κελιού σε μορφή Excel (π.χ., "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας. |
| cellName | java.lang.String | Η αναφορά κελιού σε μορφή Excel (π.χ., "A1", "C5"). |

**Επιστρέφει:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Το κελί στην καθορισμένη θέση.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Ανακτά ένα λεξικό που περιέχει τα ευρετικά και τα ονόματα όλων των διαγραμμάτων στο καθορισμένο φύλλο εργασίας ενός βιβλίου εργασίας Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| worksheetName | java.lang.String | Το όνομα του φύλλου εργασίας για την αναζήτηση διαγραμμάτων. |

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Ένα λεξικό όπου το κλειδί είναι το ευρετικό του διαγράμματος και η τιμή είναι το όνομα του διαγράμματος.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Ανακτά τα ονόματα όλων των φύλλων εργασίας που περιέχονται στο βιβλίο εργασίας Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Μια λίστα με τα ονόματα των φύλλων εργασίας