---
title: ExcelDataCell
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getValue()](#getValue--) | Gibt den in der Excel-Zelle enthaltenen Wert zurück. |
| [getName()](#getName--) | Gibt den Namen der Diagrammdatenzelle zurück. |
| [getRow()](#getRow--) | Gibt den nullbasierten Index der Zeile im Arbeitsblatt zurück, in der sich die Zelle befindet. |
| [getColumn()](#getColumn--) | Gibt den nullbasierten Index der Spalte im Arbeitsblatt zurück, in der sich die Zelle befindet. |
### getValue() {#getValue--}
```
public final Object getValue()
```


Gibt den in der Excel-Zelle enthaltenen Wert zurück.

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
public final String getName()
```


Gibt den Namen der Diagrammdatenzelle zurück.

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
public final int getRow()
```


Gibt den nullbasierten Index der Zeile im Arbeitsblatt zurück, in der sich die Zelle befindet. Nur-Lesen int.

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
public final int getColumn()
```


Gibt den nullbasierten Index der Spalte im Arbeitsblatt zurück, in der sich die Zelle befindet. Nur-Lesen int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Ausgabe: 1
> ```


**Rückgabe:**
int