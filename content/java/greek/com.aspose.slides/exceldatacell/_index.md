---
title: ExcelDataCell
second_title: Aspose.Slides για την Java API Αναφορά
description: Αντιπροσωπεύει ένα μοναδικό κελί σε ένα βιβλίο εργασίας Excel.
type: docs
url: /el/com.aspose.slides/exceldatacell/
---
**Κληρονομικότητα:**
java.lang.Object

**Όλες οι Υλοποιημένες Διεπαφές:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Αντιπροσωπεύει ένα μοναδικό κελί σε ένα βιβλίο εργασίας Excel.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getValue()](#getValue--) | Παίρνει την τιμή που περιέχεται στο κελί Excel. |
| [getName()](#getName--) | Παίρνει το όνομα του κελιού δεδομένων του διαγράμματος. |
| [getRow()](#getRow--) | Παίρνει το μηδενικό (zero-based) δείκτη της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. |
| [getColumn()](#getColumn--) | Παίρνει το μηδενικό (zero-based) δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. |
### getValue() {#getValue--}
```
public final Object getValue()
```

Παίρνει την τιμή που περιέχεται στο κελί Excel.

--------------------

> ```
> Παράδειγμα:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Επιστρέφει:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```

Παίρνει το όνομα του κελιού δεδομένων του διαγράμματος.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Έξοδος: "B2"
> ```


**Επιστρέφει:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

Παίρνει το μηδενικό (zero-based) δείκτη της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Έξοδος: 1
> ```

**Επιστρέφει:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Παίρνει το μηδενικό (zero-based) δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Έξοδος: 1
> ```


**Επιστρέφει:**
int