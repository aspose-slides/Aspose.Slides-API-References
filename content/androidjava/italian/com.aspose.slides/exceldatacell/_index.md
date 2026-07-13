---
title: ExcelDataCell
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una singola cella in una cartella di lavoro Excel.
type: docs
url: /it/com.aspose.slides/exceldatacell/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)
```
public class ExcelDataCell implements IExcelDataCell
```

Rappresenta una singola cella in una cartella di lavoro Excel.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue()](#getValue--) | Ottiene il valore contenuto nella cella Excel. |
| [getName()](#getName--) | Ottiene il nome della cella dei dati del grafico. |
| [getRow()](#getRow--) | Ottiene l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. |
| [getColumn()](#getColumn--) | Ottiene l'indice basato su zero della colonna nel foglio di lavoro in cui si trova la cella. |
### getValue() {#getValue--}
```
public final Object getValue()
```

Ottiene il valore contenuto nella cella Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Restituisce:**
java.lang.Object
### getName() {#getName--}
```
public final String getName()
```

Ottiene il nome della cella dei dati del grafico.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Risultato: "B2"
> ```


**Restituisce:**
java.lang.String
### getRow() {#getRow--}
```
public final int getRow()
```

Ottiene l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. Solo lettura int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Risultato: 1
> ```


**Restituisce:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Ottiene l'indice basato su zero della colonna nel foglio di lavoro in cui si trova la cella. Solo lettura int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //Risultato: 1
> ```


**Restituisce:**
int