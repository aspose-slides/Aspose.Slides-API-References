---
title: ExcelDataCell
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine einzelne Zelle in einer Excel-Arbeitsmappe dar.
type: docs
url: /de/com.aspose.slides/exceldatacell/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Stellt eine einzelne Zelle in einer Excel-Arbeitsmappe dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Liefert den in der Excel-Zelle enthaltenen Wert. |
| [getName()](#getName--) | Liefert den Namen der Diagrammdatenzelle. |
| [getRow()](#getRow--) | Liefert den nullbasierten Index der Zeile im Arbeitsblatt, in dem sich die Zelle befindet. Nur lesend int. |
| [getColumn()](#getColumn--) | Liefert den nullbasierten Index der Spalte im Arbeitsblatt, in dem sich die Zelle befindet. Nur lesend int. |

### getValue() {#getValue--}
```
public final Object getValue()
```

Liefert den in der Excel-Zelle enthaltenen Wert.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Rückgabewert:**
java.lang.Object

### getName() {#getName--}
```
public final String getName()
```

Liefert den Namen der Diagrammdatenzelle.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Ausgabe: "B2"
> ```

**Rückgabewert:**
java.lang.String

### getRow() {#getRow--}
```
public final int getRow()
```

Liefert den nullbasierten Index der Zeile im Arbeitsblatt, in dem sich die Zelle befindet. Nur lesend int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Ausgabe: 1
> ```


**Rückgabewert:**
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

Liefert den nullbasierten Index der Spalte im Arbeitsblatt, in dem sich die Zelle befindet. Nur lesend int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Ausgabe: 1
> ```

**Rückgabewert:**
int