---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt eine einzelne Zelle in einer Excel-Arbeitsmappe dar.
type: docs
url: /de/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Stellt eine einzelne Zelle in einer Excel-Arbeitsmappe dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue()](#getValue--) | Liefert den in der Excel-Zelle enthaltenen Wert. |
| [getName()](#getName--) | Liefert den Namen der Diagrammdatenzelle. |
| [getRow()](#getRow--) | Liefert den nullbasierten Index der Zeile im Arbeitsblatt, in dem sich die Zelle befindet. |
| [getColumn()](#getColumn--) | Liefert den nullbasierten Index der Spalte im Arbeitsblatt, in dem sich die Zelle befindet. |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Liefert den in der Excel-Zelle enthaltenen Wert. Nur lesbar Object.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Rückgabe:**
java.lang.Object

### getName() {#getName--}
```
public abstract String getName()
```

Liefert den Namen der Diagrammdatenzelle. Nur lesbar String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Ausgabe: "B2"
> ```

**Rückgabe:**
java.lang.String

### getRow() {#getRow--}
```
public abstract int getRow()
```

Liefert den nullbasierten Index der Zeile im Arbeitsblatt, in dem sich die Zelle befindet. Nur lesbar int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Ausgabe: 1
> ```


**Rückgabe:**
int

### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Liefert den nullbasierten Index der Spalte im Arbeitsblatt, in dem sich die Zelle befindet. Nur lesbar int.

--------------------

> ```
> Example:
>  
> v
> ```

**Rückgabe:**
int