---
title: IExcelDataCell
second_title: Aspose.Slides para Java - Referência da API
description: Representa uma única célula em uma pasta de trabalho do Excel.
type: docs
url: /pt/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Representa uma única célula em uma pasta de trabalho do Excel.
## Métodos

| Método | Descrição |
| --- | --- |
| [getValue()](#getValue--) | Obtém o valor contido na célula do Excel. |
| [getName()](#getName--) | Obtém o nome da célula de dados do gráfico. |
| [getRow()](#getRow--) | Obtém o índice baseado em zero da linha na planilha onde a célula está localizada. |
| [getColumn()](#getColumn--) | Obtém o índice baseado em zero da coluna na planilha onde a célula está localizada. |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtém o valor contido na célula do Excel. Somente leitura Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
>  ```


**Retorna:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


Obtém o nome da célula de dados do gráfico. Somente leitura String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //Saída: "B2"
>  ```


**Retorna:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


Obtém o índice baseado em zero da linha na planilha onde a célula está localizada. Somente leitura int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //Saída: 1
> ```


**Retorna:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Obtém o índice baseado em zero da coluna na planilha onde a célula está localizada. Somente leitura int.

--------------------

> ```
> Example:
>  
> v
> ```

**Retorna:**
int