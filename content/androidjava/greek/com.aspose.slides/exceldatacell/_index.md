---
title: ExcelDataCell
second_title: Aspose.Slides για Android μέσω Αναφοράς API Java
description: Αντιπροσωπεύει ένα μόνο κελί σε ένα βιβλίο εργασίας του Excel.
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

Αναπαριστά ένα μόνο κελί σε ένα βιβλίο εργασίας του Excel.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getValue()](#getValue--) | Λαμβάνει την τιμή που περιέχεται στο κελί του Excel. |
| [getName()](#getName--) | Λαμβάνει το όνομα του κελιού δεδομένων του διαγράμματος. |
| [getRow()](#getRow--) | Λαμβάνει το μηδενικής βάσης δείκτη της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. |
| [getColumn()](#getColumn--) | Λαμβάνει το μηδενικής βάσης δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Λαμβάνει την τιμή που περιέχεται στο κελί του Excel.

--------------------

> ```
> Example:
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


Λαμβάνει το όνομα του κελιού δεδομένων του διαγράμματος.

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


Λαμβάνει το μηδενικής βάσης δείκτη της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο ανάγνωση int.

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


Λαμβάνει το μηδενικής βάσης δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο ανάγνωση int.

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