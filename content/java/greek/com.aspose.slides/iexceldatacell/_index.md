---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Represents a single cell in an Excel workbook.
type: docs
url: /el/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Αντιπροσωπεύει ένα μοναδικό κελί σε ένα βιβλίο εργασίας Excel.
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getValue()](#getValue--) | Λαμβάνει την τιμή που περιέχεται στο κελί του Excel. |
| [getName()](#getName--) | Λαμβάνει το όνομα του κελιού δεδομένων γραφήματος. |
| [getRow()](#getRow--) | Λαμβάνει τον μηδενική βάση δείκτη της σειράς στο φύλλο εργασίας όπου βρίσκεται το κελί. |
| [getColumn()](#getColumn--) | Λαμβάνει τον μηδενική βάση δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Λαμβάνει την τιμή που περιέχεται στο κελί του Excel. Μόνο για ανάγνωση  Object .

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
public abstract String getName()
```


Λαμβάνει το όνομα του κελιού δεδομένων γραφήματος. Μόνο για ανάγνωση String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Αποτέλεσμα: "B2"
> ```

**Επιστρέφει:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Λαμβάνει τον μηδενική βάση δείκτη της σειράς στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Αποτέλεσμα: 1
> ```

**Επιστρέφει:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Λαμβάνει τον μηδενική βάση δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
> v
> ```

**Επιστρέφει:**
int