---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
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
| [getValue()](#getValue--) | Restituisce il valore contenuto nella cella Excel. |
| [getName()](#getName--) | Restituisce il nome della cella dati del grafico. |
| [getRow()](#getRow--) | Restituisce l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. |
| [getColumn()](#getColumn--) | Restituisce l'indice basato su zero della colonna nel foglio di lavoro in cui si trova la cella. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Restituisce il valore contenuto nella cella Excel. **Sola lettura**  Object .

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


Restituisce il nome della cella dati del grafico. **Sola lettura** String.

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


Restituisce l'indice basato su zero della riga nel foglio di lavoro in cui si trova la cella. **Sola lettura** int.

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
public abstract int getColumn()
```


Restituisce l'indice basato su zero della colonna nel foglio di lavoro in cui si trova la cella. **Sola lettura** int.

--------------------

> ```
> Example:
>  
> v
> ```

**Restituisce:**  
int