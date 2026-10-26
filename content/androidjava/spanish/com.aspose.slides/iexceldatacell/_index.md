---
title: IExcelDataCell
second_title: Aspose.Slides para Android vía Referencia de API de Java
description: Representa una única celda en un libro de Excel.
type: docs
url: /es/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Representa una única celda en un libro de Excel.
## Métodos

| Método | Descripción |
| --- | --- |
| [getValue()](#getValue--) | Obtiene el valor contenido en la celda de Excel. |
| [getName()](#getName--) | Obtiene el nombre de la celda de datos del gráfico. |
| [getRow()](#getRow--) | Obtiene el índice basado en cero de la fila en la hoja de cálculo donde se encuentra la celda. |
| [getColumn()](#getColumn--) | Obtiene el índice basado en cero de la columna en la hoja de cálculo donde se encuentra la celda. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtiene el valor contenido en la celda de Excel. Solo lectura  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Devuelve:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Obtiene el nombre de la celda de datos del gráfico. Solo lectura String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Salida: "B2"
> ```

**Devuelve:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Obtiene el índice basado en cero de la fila en la hoja de cálculo donde se encuentra la celda. Solo lectura int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Salida: 1
> ```


**Devuelve:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Obtiene el índice basado en cero de la columna en la hoja de cálculo donde se encuentra la celda. Solo lectura int.

--------------------

> ```
> Example:
>  
> v
> ```


**Devuelve:**
int