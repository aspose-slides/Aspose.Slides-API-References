---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a single cell in an Excel workbook.
type: docs
url: /el/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Αποκτά ένα μόνο κελί σε ένα βιβλίο εργασίας του Excel.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getValue()](#getValue--) | Αποκτά την τιμή που περιέχεται στο κελί του Excel. |
| [getName()](#getName--) | Αποκτά το όνομα του κελιού δεδομένων του διαγράμματος. |
| [getRow()](#getRow--) | Αποκτά τον μηδενικό δείκτη της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. |
| [getColumn()](#getColumn--) | Αποκτά τον μηδενικό δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Αποκτά την τιμή που περιέχεται στο κελί του Excel. Μόνο για ανάγνωση  Object .

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

Αποκτά το όνομα του κελιού δεδομένων του διαγράμματος. Μόνο για ανάγνωση String.

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

Αποκτά τον μηδενικό δείκτη της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int.

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

Αποκτά τον μηδενικό δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int.

--------------------

> ```
> Example:
>  
> v
> ```

**Επιστρέφει:**
int