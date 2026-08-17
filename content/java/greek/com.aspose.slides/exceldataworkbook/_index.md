---
title: ExcelDataWorkbook
second_title: Aspose.Slides για την Αναφορά API της Java
description: Αντιπροσωπεύει ένα βιβλίο εργασίας που παρέχει πρόσβαση στα δεδομένα Excel για γενική χρήση.
type: docs
url: /el/com.aspose.slides/exceldataworkbook/
---
**Κληρονομία:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Αντιπροσωπεύει ένα βιβλίο εργασίας που παρέχει πρόσβαση στα δεδομένα Excel για γενική χρήση.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Αρχικοποιεί μια νέα εμφάνιση χρησιμοποιώντας τη συγκεκριμένη διαδρομή αρχείου. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης χρησιμοποιώντας το παρεχόμενο ρεύμα. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Ανακτά μια συλλογή κελιών από το βιβλίο εργασίας που ταιριάζουν με τον καθορισμένο τύπο. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Ανακτά ένα κελί από το συγκεκριμένο φύλλο εργασίας χρησιμοποιώντας τον δείκτη του και τις συντεταγμένες κελιού. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Ανακτά ένα κελί από το συγκεκριμένο φύλλο εργασίας χρησιμοποιώντας το όνομα του και τις συντεταγμένες κελιού. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Ανακτά ένα κελί από το συγκεκριμένο φύλλο εργασίας χρησιμοποιώντας τον δείκτη του και το όνομα κελιού τύπου Excel (π.χ., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Ανακτά ένα κελί από το συγκεκριμένο φύλλο εργασίας χρησιμοποιώντας το όνομα κελιού τύπου Excel (π.χ., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Ανακτά ένα λεξικό που περιέχει τους δείκτες και τα ονόματα όλων των διαγραμμάτων στο συγκεκριμένο φύλλο εργασίας ενός βιβλίου εργασίας Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Ανακτά τα ονόματα όλων των φύλλων εργασίας που περιέχονται στο βιβλίο εργασίας Excel. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```


Αρχικοποιεί μια νέα εμφάνιση χρησιμοποιώντας τη συγκεκριμένη διαδρομή αρχείου.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Η πλήρης διαδρομή προς το αρχείο του βιβλίου εργασίας Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```


Αρχικοποιεί μια νέα εμφάνιση της κλάσης χρησιμοποιώντας το παρεχόμενο ρεύμα.

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Ένα ρεύμα που περιέχει τα δεδομένα του βιβλίου εργασίας Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


Ανακτά μια συλλογή κελιών από το βιβλίο εργασίας που ταιριάζουν με τον καθορισμένο τύπο.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Έξοδος: 5
> ```


**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | java.lang.String | Ένας τύπος ή έκφραση περιοχής (π.χ., "Sheet1!A1:B3") που χρησιμοποιείται για τον εντοπισμό των κελιών-στόχων. |
| skipHiddenCells | boolean | Εάν είναι true, τα κρυμμένα κελιά (π.χ., σε κρυφές γραμμές ή στήλες) θα εξαιρεθούν από το αποτέλεσμα. |

**Επιστρέφει:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Μία λίστα μόνο για ανάγνωση από κελί που ταιριάζουν με τον καθορισμένο τύπο.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


Ανακτά ένα κελί από το συγκεκριμένο φύλλο εργασίας χρησιμοποιώντας τον δείκτη του και τις συντεταγμένες κελιού.

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
| worksheetIndex | int | Δείκτης φύλλου εργασίας με βάση το μηδέν. |
| row | int | Δείκτης γραμμής του κελιού με βάση το μηδέν. |
| column | int | Δείκτης στήλης του κελιού με βάση το μηδέν. |

**Επιστρέφει:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Το κελί στην καθορισμένη θέση.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```


Ανακτά ένα κελί από το συγκεκριμένο φύλλο εργασίας χρησιμοποιώντας το όνομά του και τις συντεταγμένες κελιού.

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
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```


Ανακτά ένα κελί από το συγκεκριμένο φύλλο εργασίας χρησιμοποιώντας τον δείκτη του και το όνομα κελιού τύπου Excel (π.χ., "B2").

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
| worksheetIndex | int | Δείκτης φύλλου εργασίας με βάση το μηδέν. |
| cellName | java.lang.String | Η αναφορά κελιού τύπου Excel (π.χ., "A1", "C5"). |

**Επιστρέφει:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Το κελί στην καθορισμένη θέση.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```


Ανακτά ένα κελί από το συγκεκριμένο φύλλο εργασίας χρησιμοποιώντας το όνομα κελιού τύπου Excel (π.χ., "B2").

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
| cellName | java.lang.String | Η αναφορά κελιού τύπου Excel (π.χ., "A1", "C5"). |

**Επιστρέφει:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Το κελί στην καθορισμένη θέση.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Ανακτά ένα λεξικό που περιέχει τους δείκτες και τα ονόματα όλων των διαγραμμάτων στο συγκεκριμένο φύλλο εργασίας ενός βιβλίου εργασίας Excel.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Ένα λεξικό όπου το κλειδί είναι ο δείκτης του διαγράμματος και η τιμή είναι το όνομα του διαγράμματος.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
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