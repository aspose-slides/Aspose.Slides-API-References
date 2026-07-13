---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta una singola cella in una cartella di lavoro Excel.
type: docs
url: /it/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Rappresenta una singola cella in una cartella di lavoro Excel.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue()](#getValue--) | Ottiene il valore contenuto nella cella Excel. |
| [getName()](#getName--) | Ottiene il nome della cella dati del grafico. |
| [getRow()](#getRow--) | Ottiene l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. |
| [getColumn()](#getColumn--) | Ottiene l'indice basato su zero della colonna nel foglio di lavoro in cui si trova la cella. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Ottiene il valore contenuto nella cella Excel. Solo lettura  Object .

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
public abstract String getName()
```


Ottiene il nome della cella dati del grafico. Solo lettura String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Output: "B2"
> ```

**Restituisce:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Ottiene l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. Solo lettura int.

--------------------

> ```
> Esempio:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Output: 1
> ```

**Restituisce:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Ottiene l'indice basato su zero della colonna nel foglio di lavoro in cui si trova la cella. Solo lettura int.

--------------------

> ```
> Example:
>  
> v
> ```

**Restituisce:**
int